# Function: <code>xhci_dbc_do_handle_events</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586657681,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:641",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586921396,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:649",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587078388,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:650",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:648",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342816,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
    },
    {
      "addr": 18446744071587345798,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587545184,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
    },
    {
      "addr": 18446744071587547591,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408736,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071588410640,
      "name": "xhci_dbc_do_handle_events.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:750",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588439248,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    },
    {
      "addr": 18446744071591569216,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:750",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588322208,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071591512383,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:750",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979728,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071592615473,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:750",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590412480,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446744071594498477,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592050416,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:750",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592050416,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592473120,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:750",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592473120,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593214752,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:761",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593214752,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500686872,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500686872,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1504
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233145380,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233145380,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1488
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294118688,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294118688,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2504
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277542868,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277542868,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1566
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009968,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
    },
    {
      "addr": 18446744071587012375,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587499744,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
    },
    {
      "addr": 18446744071587502151,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_do_handle_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_do_handle_events",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:647",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607520,
      "name": "xhci_dbc_do_handle_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
    },
    {
      "addr": 18446744071587610023,
      "name": "xhci_dbc_do_handle_events.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc * dbc)
```
</details>
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
