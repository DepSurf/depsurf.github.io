# Function: <code>xhci_dbc_queue_bulk_tx</code>

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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586659710,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586923471,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:240",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587080462,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:240",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587344450,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:240",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587544393,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588407664,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407664,
      "name": "xhci_dbc_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588437968,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:245",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437968,
      "name": "xhci_dbc_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320800,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:245",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320800,
      "name": "xhci_dbc_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588978336,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:245",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978336,
      "name": "xhci_dbc_queue_bulk_tx",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590413264,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:245",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590413264,
      "name": "xhci_dbc_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592048944,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:245",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592048944,
      "name": "xhci_dbc_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592471648,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:245",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592471648,
      "name": "xhci_dbc_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593213280,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:260",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593213280,
      "name": "xhci_dbc_queue_bulk_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500689372,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233144364,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294122340,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277546828,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587009177,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587498953,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
  "name": "xhci_dbc_queue_bulk_tx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587606681,
      "name": "xhci_dbc_queue_bulk_tx",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:239",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
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
int xhci_dbc_queue_bulk_tx(struct dbc_ep * dep, struct dbc_request * req)
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
