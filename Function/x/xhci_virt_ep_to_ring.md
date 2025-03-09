# Function: <code>xhci_virt_ep_to_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_virt_ep_to_ring(struct xhci_hcd * xhci, struct xhci_virt_ep * ep, unsigned int stream_id)
```

```json
{
  "name": "xhci_virt_ep_to_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591508543,
      "name": "xhci_virt_ep_to_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:492",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591508543,
      "name": "xhci_virt_ep_to_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588263264,
      "name": "xhci_virt_ep_to_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591508583,
      "name": "xhci_virt_ep_to_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
struct xhci_ring * xhci_virt_ep_to_ring(struct xhci_hcd * xhci, struct xhci_virt_ep * ep, unsigned int stream_id)
```

```json
{
  "name": "xhci_virt_ep_to_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592609978,
      "name": "xhci_virt_ep_to_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:505",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592609978,
      "name": "xhci_virt_ep_to_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588914160,
      "name": "xhci_virt_ep_to_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071592610018,
      "name": "xhci_virt_ep_to_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "xhci_virt_ep_to_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590371167,
      "name": "xhci_virt_ep_to_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:505",
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
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590343824,
      "name": "xhci_virt_ep_to_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071594493020,
      "name": "xhci_virt_ep_to_ring.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_virt_ep_to_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592004863,
      "name": "xhci_virt_ep_to_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:505",
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
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591972864,
      "name": "xhci_virt_ep_to_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_virt_ep_to_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592425599,
      "name": "xhci_virt_ep_to_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:559",
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
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592393920,
      "name": "xhci_virt_ep_to_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_virt_ep_to_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593169343,
      "name": "xhci_virt_ep_to_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:567",
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
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593136864,
      "name": "xhci_virt_ep_to_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct xhci_ring * xhci_virt_ep_to_ring(struct xhci_hcd * xhci, struct xhci_virt_ep * ep, unsigned int stream_id)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct xhci_ring * xhci_virt_ep_to_ring(struct xhci_hcd * xhci, struct xhci_virt_ep * ep, unsigned int stream_id)
```
</details>
</li>
</ul>
