# Function: <code>xhci_get_usb3_port_status</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587053156,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:908",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587316371,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:918",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587517524,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379136,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:930",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379136,
      "name": "xhci_get_usb3_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588406064,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:930",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406064,
      "name": "xhci_get_usb3_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289072,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:1016",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289072,
      "name": "xhci_get_usb3_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:1018",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588942640,
      "name": "xhci_get_usb3_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
    },
    {
      "addr": 18446744071592614072,
      "name": "xhci_get_usb3_port_status.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:1019",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590374448,
      "name": "xhci_get_usb3_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    },
    {
      "addr": 18446744071594497286,
      "name": "xhci_get_usb3_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:1033",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592008784,
      "name": "xhci_get_usb3_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    },
    {
      "addr": 18446744071596301013,
      "name": "xhci_get_usb3_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:1033",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592429456,
      "name": "xhci_get_usb3_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
    },
    {
      "addr": 18446744071596830529,
      "name": "xhci_get_usb3_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:1033",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593173200,
      "name": "xhci_get_usb3_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
    },
    {
      "addr": 18446744071597754489,
      "name": "xhci_get_usb3_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500658112,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233117276,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294082096,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277520224,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587223556,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586982308,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587472084,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_get_usb3_port_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587579748,
      "name": "xhci_get_usb3_port_status",
      "external": false,
      "loc": "drivers/usb/host/xhci-hub.c:927",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port * port, u32 * status, u32 portsc)
```
</details>
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
