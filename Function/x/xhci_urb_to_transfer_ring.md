# Function: <code>xhci_urb_to_transfer_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct xhci_ring * xhci_urb_to_transfer_ring(struct xhci_hcd * xhci, struct urb * urb)
```

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585447561,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.c:1460",
      "file": "drivers/usb/host/xhci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585494624,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:411",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585494624,
      "name": "xhci_urb_to_transfer_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585843237,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:1982",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585896850,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:1982",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
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
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586031948,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:1979",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586085890,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:1979",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
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
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586114588,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2101",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586168127,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2101",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586559084,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2124",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586613423,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2124",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586823533,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2136",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586880293,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2136",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586980141,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2144",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587035861,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2144",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587240668,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2160",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587299260,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2160",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587441932,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587500460,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588307778,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2173",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588369736,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2173",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588342507,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2188",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588399928,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2188",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588225065,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2194",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588286364,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2194",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588868634,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2201",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588939708,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2201",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590295234,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2228",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590371133,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2228",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591918674,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2229",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592004829,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2229",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592340786,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2239",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592425565,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2239",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593082034,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2216",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593169309,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2216",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500576668,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500641520,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233035632,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 3233100536,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293978304,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294061644,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277447768,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277506254,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
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
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587148012,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587206492,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586906620,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586965244,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587396492,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587455020,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_urb_to_transfer_ring",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587502892,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587562364,
      "name": "xhci_urb_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2170",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct xhci_ring * xhci_urb_to_transfer_ring(struct xhci_hcd * xhci, struct urb * urb)
```
</details>
</li>
</ul>
