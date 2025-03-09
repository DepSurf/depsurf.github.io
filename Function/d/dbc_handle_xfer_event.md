# Function: <code>dbc_handle_xfer_event</code>

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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586658303,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:584",
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586921944,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:592",
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587078678,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:593",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587343114,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:591",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587545482,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void dbc_handle_xfer_event(struct xhci_hcd * xhci, union xhci_trb * event)
```

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408352,
      "name": "dbc_handle_xfer_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071588410599,
      "name": "dbc_handle_xfer_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void dbc_handle_xfer_event(struct xhci_dbc * dbc, union xhci_trb * event)
```

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:682",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438880,
      "name": "dbc_handle_xfer_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071591569178,
      "name": "dbc_handle_xfer_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void dbc_handle_xfer_event(struct xhci_dbc * dbc, union xhci_trb * event)
```

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:682",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588321840,
      "name": "dbc_handle_xfer_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071591512337,
      "name": "dbc_handle_xfer_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void dbc_handle_xfer_event(struct xhci_dbc * dbc, union xhci_trb * event)
```

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:682",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979360,
      "name": "dbc_handle_xfer_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071592615427,
      "name": "dbc_handle_xfer_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void dbc_handle_xfer_event(struct xhci_dbc * dbc, union xhci_trb * event)
```

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:682",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590412080,
      "name": "dbc_handle_xfer_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071594498433,
      "name": "dbc_handle_xfer_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void dbc_handle_xfer_event(struct xhci_dbc * dbc, union xhci_trb * event)
```

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592049904,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:682",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592049904,
      "name": "dbc_handle_xfer_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void dbc_handle_xfer_event(struct xhci_dbc * dbc, union xhci_trb * event)
```

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592472624,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:682",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592472624,
      "name": "dbc_handle_xfer_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void dbc_handle_xfer_event(struct xhci_dbc * dbc, union xhci_trb * event)
```

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593214256,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:693",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593214256,
      "name": "dbc_handle_xfer_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500687528,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233145936,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294119144,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277543294,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587010266,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587500042,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "dbc_handle_xfer_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587607818,
      "name": "dbc_handle_xfer_event",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:590",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
void dbc_handle_xfer_event(struct xhci_hcd * xhci, union xhci_trb * event)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_dbc * dbc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xhci_hcd * xhci</code>
</li>
</ul>
</details>
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
