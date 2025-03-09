# Function: <code>finish_td</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, union xhci_trb * event_trb, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status, bool skip)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585508880,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1801",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508880,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585904288,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
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
      "addr": 18446744071585904288,
      "name": "finish_td.constprop.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586093488,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1841",
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
      "addr": 18446744071586093488,
      "name": "finish_td.constprop.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586176752,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1932",
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
      "addr": 18446744071586176752,
      "name": "finish_td.isra.64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586622064,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1926",
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
      "addr": 18446744071586622064,
      "name": "finish_td.isra.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586889152,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1849",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586889152,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587044896,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1897",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044896,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587305328,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305328,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587506544,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506544,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588357648,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1969",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588357648,
      "name": "finish_td.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588387968,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1974",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588387968,
      "name": "finish_td.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588270128,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2137",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270128,
      "name": "finish_td.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588921728,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2202",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921728,
      "name": "finish_td.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590352464,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2136",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590352464,
      "name": "finish_td.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591982976,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2138",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591982976,
      "name": "finish_td.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592405328,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2160",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592405328,
      "name": "finish_td.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593148240,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2165",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593148240,
      "name": "finish_td.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500648288,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500648288,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233107540,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233107540,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294070144,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294070144,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277512128,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277512128,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587212576,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587212576,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586971328,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586971328,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587461104,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461104,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
```

```json
{
  "name": "finish_td",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568672,
      "name": "finish_td",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1943",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568672,
      "name": "finish_td",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, union xhci_trb * event_trb, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status, bool skip)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int finish_td(struct xhci_hcd * xhci, struct xhci_td * td, struct xhci_transfer_event * event, struct xhci_virt_ep * ep, int * status)
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
