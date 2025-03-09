# Function: <code>xhci_ring_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585479152,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:276",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_free_or_cache_endpoint_ring",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585479152,
      "name": "xhci_ring_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585875072,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:286",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_or_cache_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585875072,
      "name": "xhci_ring_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586063920,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:286",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_or_cache_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586063920,
      "name": "xhci_ring_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586153862,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:286",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142880,
      "name": "xhci_ring_free.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071586146320,
      "name": "xhci_ring_free",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586599291,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:275",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586587824,
      "name": "xhci_ring_free.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071586590768,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586862299,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852448,
      "name": "xhci_ring_free.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071586853488,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587018411,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008848,
      "name": "xhci_ring_free.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071587009888,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587281515,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587270336,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587273088,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587482155,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470720,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587473664,
      "name": "xhci_ring_free",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588344995,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333264,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071588336400,
      "name": "xhci_ring_free",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588376579,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:280",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364464,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    },
    {
      "addr": 18446744071588367712,
      "name": "xhci_ring_free",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588258947,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:280",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588247312,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    },
    {
      "addr": 18446744071588250240,
      "name": "xhci_ring_free",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588909571,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:280",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895568,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    },
    {
      "addr": 18446744071588899040,
      "name": "xhci_ring_free",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590339111,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:280",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590324640,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071590328240,
      "name": "xhci_ring_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591967671,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:280",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591952048,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071591955776,
      "name": "xhci_ring_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592391615,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:280",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592373136,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071592376960,
      "name": "xhci_ring_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593120522,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:287",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593115120,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071593119456,
      "name": "xhci_ring_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500619492,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500607992,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446603336500609888,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233079776,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233067928,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 3233071060,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294034924,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294018544,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 13835058055294023280,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277487358,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277476384,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446743936277479184,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587188187,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176752,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587179696,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586946939,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935504,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071586938448,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587436715,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587425280,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071587428224,
      "name": "xhci_ring_free",
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
void xhci_ring_free(struct xhci_hcd * xhci, struct xhci_ring * ring)
```

```json
{
  "name": "xhci_ring_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587543691,
      "name": "xhci_ring_free",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:277",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_endpoint_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532128,
      "name": "xhci_ring_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071587535088,
      "name": "xhci_ring_free",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
