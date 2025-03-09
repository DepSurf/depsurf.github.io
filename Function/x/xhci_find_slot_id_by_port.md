# Function: <code>xhci_find_slot_id_by_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585518432,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:351",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585518432,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585922365,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:351",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913536,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586110702,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:351",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101616,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194968,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185152,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586640754,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:348",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630752,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586906794,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:351",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586896192,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587063798,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:351",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052560,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587327271,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:351",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587315584,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587528791,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516736,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588390762,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381456,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588417752,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408368,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588300870,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:446",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291408,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588958037,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:447",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945232,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590389925,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:447",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590376512,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592024267,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:460",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592007152,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592443869,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:460",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592427872,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593187597,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:460",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593171616,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500670424,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500657104,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233128452,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233116520,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294095924,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294080688,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277530756,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277519392,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587234823,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587222768,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586993575,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981520,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587483351,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471296,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int xhci_find_slot_id_by_port(struct usb_hcd * hcd, struct xhci_hcd * xhci, u16 port)
```

```json
{
  "name": "xhci_find_slot_id_by_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587591079,
      "name": "xhci_find_slot_id_by_port",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:360",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578960,
      "name": "xhci_find_slot_id_by_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
