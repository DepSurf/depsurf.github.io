# Function: <code>td_to_noop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void td_to_noop(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, struct xhci_td * cur_td, bool flip_cycle)
```

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585495056,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:531",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495056,
      "name": "td_to_noop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585890592,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:513",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890592,
      "name": "td_to_noop.constprop.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586079744,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:596",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079744,
      "name": "td_to_noop.constprop.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586161008,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:610",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161008,
      "name": "td_to_noop.constprop.67",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586606000,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:599",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606000,
      "name": "td_to_noop.constprop.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586871264,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:599",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586871264,
      "name": "td_to_noop.constprop.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587026576,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:599",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026576,
      "name": "td_to_noop.constprop.64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587288848,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288848,
      "name": "td_to_noop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587489792,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587489792,
      "name": "td_to_noop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588351456,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:630",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588351456,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588382496,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:630",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588382496,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588264496,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:687",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264496,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588915376,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:723",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588915376,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590345184,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:723",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590345184,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591974624,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:723",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591974624,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592396080,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:754",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396080,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593139040,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:762",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593139040,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500626272,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500626272,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233088636,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233088636,
      "name": "td_to_noop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294045744,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294045744,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277495256,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277495256,
      "name": "td_to_noop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587195824,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587195824,
      "name": "td_to_noop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586954576,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954576,
      "name": "td_to_noop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587444352,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444352,
      "name": "td_to_noop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "td_to_noop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587551808,
      "name": "td_to_noop",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:606",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587551808,
      "name": "td_to_noop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void td_to_noop(struct xhci_hcd * xhci, struct xhci_ring * ep_ring, struct xhci_td * cur_td, bool flip_cycle)
```
</details>
</li>
</ul>
