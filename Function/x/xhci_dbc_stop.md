# Function: <code>xhci_dbc_stop</code>

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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586655200,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:542",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586655200,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586918768,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:547",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918768,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587076016,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:546",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587076016,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:544",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587340560,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    },
    {
      "addr": 18446744071587345590,
      "name": "xhci_dbc_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587542192,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587542192,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588404768,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588404768,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void xhci_dbc_stop(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588437216,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:629",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437216,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
void xhci_dbc_stop(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320208,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:629",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320208,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
void xhci_dbc_stop(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588977744,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:629",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977744,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
void xhci_dbc_stop(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590411248,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:629",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590411248,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
void xhci_dbc_stop(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592048176,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:629",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592048176,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void xhci_dbc_stop(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592470864,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:629",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592470864,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void xhci_dbc_stop(struct xhci_dbc * dbc)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593216368,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:640",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593216368,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500684920,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500684920,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233142136,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233142136,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294115424,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294115424,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277542080,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277542080,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587006976,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587006976,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587496752,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587496752,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
```

```json
{
  "name": "xhci_dbc_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587604480,
      "name": "xhci_dbc_stop",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:543",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587604480,
      "name": "xhci_dbc_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
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
void xhci_dbc_stop(struct xhci_hcd * xhci)
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
