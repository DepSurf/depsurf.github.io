# Function: <code>xhci_alloc_container_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476960,
      "name": "xhci_alloc_container_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:503",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476960,
      "name": "xhci_alloc_container_ctx.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585871792,
      "name": "xhci_alloc_container_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:516",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871792,
      "name": "xhci_alloc_container_ctx.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586060640,
      "name": "xhci_alloc_container_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:516",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060640,
      "name": "xhci_alloc_container_ctx.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586143104,
      "name": "xhci_alloc_container_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:470",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586143104,
      "name": "xhci_alloc_container_ctx.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586591712,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:457",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586591712,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586854448,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586854448,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010880,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010880,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587274080,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587274080,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587474656,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587474656,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588337424,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337424,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588369072,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:469",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369072,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588251584,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:469",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251584,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588900560,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:469",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900560,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590329728,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:468",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590329728,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591957360,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:468",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591957360,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592378496,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592378496,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593121920,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:471",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593121920,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500611056,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500611056,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233072164,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233072164,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294024736,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294024736,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277480136,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277480136,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587180688,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587180688,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586939440,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586939440,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587429216,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587429216,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
```

```json
{
  "name": "xhci_alloc_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587536128,
      "name": "xhci_alloc_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:460",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587536128,
      "name": "xhci_alloc_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_container_ctx * xhci_alloc_container_ctx(struct xhci_hcd * xhci, int type, gfp_t flags)
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
