# Function: <code>xhci_td_remainder</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585494416,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3062",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585494416,
      "name": "xhci_td_remainder.isra.20.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585889632,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3104",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585889632,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586078736,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3005",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078736,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586159920,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3105",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159920,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603680,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3109",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603680,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586869216,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3028",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586869216,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024528,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3092",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024528,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286016,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3138",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286016,
      "name": "xhci_td_remainder",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587486800,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587486800,
      "name": "xhci_td_remainder",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588349008,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3211",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588349008,
      "name": "xhci_td_remainder",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379856,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3221",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379856,
      "name": "xhci_td_remainder",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262240,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3410",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262240,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588913104,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3480",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913104,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590342656,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3415",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590342656,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591971488,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3422",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591971488,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592392544,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3442",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592392544,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593135488,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3485",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593135488,
      "name": "xhci_td_remainder",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500625664,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500625664,
      "name": "xhci_td_remainder.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233083760,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233083760,
      "name": "xhci_td_remainder",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294042624,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294042624,
      "name": "xhci_td_remainder.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277492612,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277492612,
      "name": "xhci_td_remainder.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192832,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192832,
      "name": "xhci_td_remainder",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951584,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951584,
      "name": "xhci_td_remainder",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587441360,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441360,
      "name": "xhci_td_remainder",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```

```json
{
  "name": "xhci_td_remainder",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587548336,
      "name": "xhci_td_remainder",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548336,
      "name": "xhci_td_remainder",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 xhci_td_remainder(struct xhci_hcd * xhci, int transferred, int trb_buff_len, unsigned int td_total_len, struct urb * urb, bool more_trbs_coming)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
