# Function: <code>trb_in_td</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585498064,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1673",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585498064,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585893856,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1698",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893856,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586082912,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1714",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586082912,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586165024,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1761",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165024,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586610272,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1755",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610272,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586877216,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1680",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877216,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587032720,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1728",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032720,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312776,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587295888,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587514034,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587496864,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1774",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377107,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071588364592,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1779",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591567675,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071588394832,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2019",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591510872,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071588277520,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2084",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592612513,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071588929248,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2018",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594495612,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071590359712,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591991952,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2020",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591991952,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592414368,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2042",
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
      "addr": 18446744071592414368,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593157872,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2047",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593157872,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500637904,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500637904,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233096768,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233096768,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294057408,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294057408,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277503188,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277503188,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587220066,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587202896,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978818,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586961648,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468594,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587451424,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct xhci_segment * trb_in_td(struct xhci_hcd * xhci, struct xhci_segment * start_seg, union xhci_trb * start_trb, union xhci_trb * end_trb, dma_addr_t suspect_dma, bool debug)
```

```json
{
  "name": "trb_in_td",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trb_in_td",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1748",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587576197,
      "name": "trb_in_td.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587558720,
      "name": "trb_in_td",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
