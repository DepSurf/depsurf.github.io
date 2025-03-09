# Function: <code>xhci_dbc_giveback</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586657216,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586657216,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920928,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920928,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587077888,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077888,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587342496,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342496,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587544864,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587544864,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588407184,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407184,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588438672,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438672,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588321632,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588321632,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588979152,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979152,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590411840,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590411840,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592048544,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592048544,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592471248,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:134",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592471248,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593212880,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:149",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593212880,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500684360,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500684360,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233145024,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233145024,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294116000,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294116000,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277542544,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277542544,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009648,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009648,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587499424,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587499424,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void xhci_dbc_giveback(struct dbc_request * req, int status)
```

```json
{
  "name": "xhci_dbc_giveback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587607184,
      "name": "xhci_dbc_giveback",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:133",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607184,
      "name": "xhci_dbc_giveback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void xhci_dbc_giveback(struct dbc_request * req, int status)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void xhci_dbc_giveback(struct dbc_request * req, int status)
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
