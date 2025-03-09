# Function: <code>inc_deq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585491600,
      "name": "inc_deq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:143",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585491600,
      "name": "inc_deq",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585889456,
      "name": "inc_deq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:134",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585889456,
      "name": "inc_deq.isra.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
  "name": "inc_deq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586078560,
      "name": "inc_deq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:153",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078560,
      "name": "inc_deq.isra.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
  "name": "inc_deq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586159680,
      "name": "inc_deq",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:168",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159680,
      "name": "inc_deq.isra.29",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586607584,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607584,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586873072,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586873072,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587028416,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028416,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587292288,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292288,
      "name": "inc_deq",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587493232,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493232,
      "name": "inc_deq",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588355792,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588355792,
      "name": "inc_deq",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588386112,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588386112,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:158",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591509194,
      "name": "inc_deq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071588267424,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:158",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592610694,
      "name": "inc_deq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071588918448,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:158",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594493748,
      "name": "inc_deq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071590350000,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591980224,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:158",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591980224,
      "name": "inc_deq",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592402928,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:158",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592402928,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593147872,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:158",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593147872,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500633008,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500633008,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233092376,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233092376,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294051456,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294051456,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277498916,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277498916,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587199264,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587199264,
      "name": "inc_deq",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586958016,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586958016,
      "name": "inc_deq",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447792,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447792,
      "name": "inc_deq",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "inc_deq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587555056,
      "name": "inc_deq",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:156",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587555056,
      "name": "inc_deq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void inc_deq(struct xhci_hcd * xhci, struct xhci_ring * ring)
```
</details>
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
