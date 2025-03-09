# Function: <code>xhci_get_rhub</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586906314,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:544",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898240,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587064373,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:544",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054864,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587327669,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:545",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587315888,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587529189,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517040,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588391157,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381760,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588418157,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408672,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588301181,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:640",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291712,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588958589,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:641",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945856,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590390621,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:641",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590377184,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592025085,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:655",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592012208,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592444653,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:662",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592432720,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593188381,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:662",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593176384,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500671088,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500657496,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233128920,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233116832,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294097072,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294081168,
      "name": "xhci_get_rhub",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277531364,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277519708,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587235221,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587223072,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586993973,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981824,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587483749,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471600,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
```

```json
{
  "name": "xhci_get_rhub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587591477,
      "name": "xhci_get_rhub",
      "external": true,
      "loc": "drivers/usb/host/xhci-hub.c:554",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587579264,
      "name": "xhci_get_rhub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct xhci_hub * xhci_get_rhub(struct usb_hcd * hcd)
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
