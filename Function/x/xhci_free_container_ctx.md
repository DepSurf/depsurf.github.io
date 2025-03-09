# Function: <code>xhci_free_container_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585475504,
      "name": "xhci_free_container_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:529",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_free_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585475504,
      "name": "xhci_free_container_ctx.isra.22",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585870992,
      "name": "xhci_free_container_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:541",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870992,
      "name": "xhci_free_container_ctx.isra.22",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586059840,
      "name": "xhci_free_container_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:541",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059840,
      "name": "xhci_free_container_ctx.isra.25",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586151024,
      "name": "xhci_free_container_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:495",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142112,
      "name": "xhci_free_container_ctx.isra.26.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586596768,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:482",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586588048,
      "name": "xhci_free_container_ctx.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586591936,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586859616,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852672,
      "name": "xhci_free_container_ctx.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586854672,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587016240,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009072,
      "name": "xhci_free_container_ctx.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587011120,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587279345,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587270576,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587274320,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587479985,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470960,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587474896,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588345052,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337664,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588376636,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:495",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369312,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588259004,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:495",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251824,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588909628,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:495",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900880,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590332756,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:494",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590330048,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591960737,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:494",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591957696,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592381873,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592378832,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593125353,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:497",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593122272,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500617144,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500607304,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336500611320,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233077556,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233068268,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3233072388,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294031752,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294018896,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055294025104,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277485324,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277476612,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446743936277480348,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587186017,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176992,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587180928,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586944769,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935744,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586939680,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587434545,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587425520,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587429456,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_free_container_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587541505,
      "name": "xhci_free_container_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:486",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_command",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532384,
      "name": "xhci_free_container_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587536368,
      "name": "xhci_free_container_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void xhci_free_container_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
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
