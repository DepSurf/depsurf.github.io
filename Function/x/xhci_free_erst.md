# Function: <code>xhci_free_erst</code>

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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586599088,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1800",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599088,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586862096,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1821",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862096,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587018272,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1821",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018272,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587281376,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1821",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281376,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587482016,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482016,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588344928,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588344816,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588376512,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1835",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376400,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588258880,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1822",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258768,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588909504,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1822",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909392,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590339044,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1813",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590338912,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591967604,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1822",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591967456,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500619344,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500619344,
      "name": "xhci_free_erst",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233079624,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233079624,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294034704,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294034704,
      "name": "xhci_free_erst",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277487214,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277487214,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587188048,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587188048,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586946800,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586946800,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436576,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436576,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```

```json
{
  "name": "xhci_free_erst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587543552,
      "name": "xhci_free_erst",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1827",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587543552,
      "name": "xhci_free_erst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void xhci_free_erst(struct xhci_hcd * xhci, struct xhci_erst * erst)
```
</details>
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
