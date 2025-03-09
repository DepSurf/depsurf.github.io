# Function: <code>xhci_hc_died</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586181771,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586163664,
      "name": "xhci_hc_died.part.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071586164176,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586627195,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:896",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586608912,
      "name": "xhci_hc_died.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071586609424,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586894788,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:896",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875872,
      "name": "xhci_hc_died.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071586876384,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587051157,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:896",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031376,
      "name": "xhci_hc_died.part.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071587031888,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587310620,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312113,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071587312607,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587295168,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587511848,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587513371,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071587513865,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587496144,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588374858,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:929",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376909,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071588377042,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071588363712,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588404954,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:934",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591567477,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071591567610,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071588393952,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588284469,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1167",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591510318,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071591510806,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588276640,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588937690,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1226",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592611887,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    },
    {
      "addr": 18446744071592612447,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071588928208,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590368927,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1218",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594494879,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    },
    {
      "addr": 18446744071594495463,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071590358688,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592002391,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1220",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591990128,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
    },
    {
      "addr": 18446744071591990672,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592423141,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1251",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592412528,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
    },
    {
      "addr": 18446744071592413072,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593166895,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:1259",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593155984,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
    },
    {
      "addr": 18446744071593156528,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500653924,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500655048,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    },
    {
      "addr": 18446603336500636616,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233114124,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233114912,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    },
    {
      "addr": 3233095780,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294077172,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294078384,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 13835058055294055840,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277517150,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277517914,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446743936277502160,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587217880,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587219403,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071587219897,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587202176,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586976632,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978155,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071586978649,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071586960928,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587466408,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587467931,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071587468425,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587450704,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_hc_died",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587574033,
      "name": "xhci_hc_died",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:907",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587575534,
      "name": "xhci_hc_died.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071587576028,
      "name": "xhci_hc_died.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587558000,
      "name": "xhci_hc_died",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void xhci_hc_died(struct xhci_hcd * xhci)
```
</details>
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
