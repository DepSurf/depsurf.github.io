# Function: <code>xhci_get_virt_ep</code>

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
struct xhci_virt_ep * xhci_get_virt_ep(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_virt_ep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588272661,
      "name": "xhci_get_virt_ep",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:472",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262368,
      "name": "xhci_get_virt_ep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071591508400,
      "name": "xhci_get_virt_ep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
struct xhci_virt_ep * xhci_get_virt_ep(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_virt_ep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588924581,
      "name": "xhci_get_virt_ep",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:485",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913232,
      "name": "xhci_get_virt_ep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071592609834,
      "name": "xhci_get_virt_ep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct xhci_virt_ep * xhci_get_virt_ep(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_virt_ep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590358197,
      "name": "xhci_get_virt_ep",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:485",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590342832,
      "name": "xhci_get_virt_ep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071594492893,
      "name": "xhci_get_virt_ep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
struct xhci_virt_ep * xhci_get_virt_ep(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_virt_ep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591971680,
      "name": "xhci_get_virt_ep",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:485",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591971680,
      "name": "xhci_get_virt_ep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct xhci_virt_ep * xhci_get_virt_ep(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_virt_ep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592392736,
      "name": "xhci_get_virt_ep",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:539",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592392736,
      "name": "xhci_get_virt_ep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct xhci_virt_ep * xhci_get_virt_ep(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_virt_ep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593135680,
      "name": "xhci_get_virt_ep",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:547",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593135680,
      "name": "xhci_get_virt_ep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct xhci_virt_ep * xhci_get_virt_ep(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index)
```
</details>
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
