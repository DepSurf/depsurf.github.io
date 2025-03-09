# Function: <code>xhci_free_stream_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585485488,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:800",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_free_streams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485488,
      "name": "xhci_free_stream_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585881280,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:815",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881280,
      "name": "xhci_free_stream_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586070128,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:815",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070128,
      "name": "xhci_free_stream_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586152000,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:769",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152000,
      "name": "xhci_free_stream_info.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071586152288,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586597728,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:756",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586597728,
      "name": "xhci_free_stream_info.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071586598016,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586861179,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586860688,
      "name": "xhci_free_stream_info.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071586860976,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587017563,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017136,
      "name": "xhci_free_stream_info.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071587017360,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587280683,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280272,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587280496,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587481323,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587480912,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587481136,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588338699,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333600,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071588338144,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370347,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:771",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364784,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071588369792,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588252731,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:754",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248064,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071588252192,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588901997,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:754",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588896720,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071588901264,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590331255,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:753",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590325440,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071590330512,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591959078,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:758",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591952880,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071591958256,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592380214,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:740",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592373968,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071592379392,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593123670,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:751",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593115904,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071593122832,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500618496,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500618024,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446603336500618320,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233078828,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233078412,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 3233078644,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294033524,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294032896,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 13835058055294033312,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277486528,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277486100,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446743936277486346,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587187355,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587186944,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587187168,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586946107,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586945696,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071586945920,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587435883,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587435472,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587435696,
      "name": "xhci_free_stream_info",
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
void xhci_free_stream_info(struct xhci_hcd * xhci, struct xhci_stream_info * stream_info)
```

```json
{
  "name": "xhci_free_stream_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587542843,
      "name": "xhci_free_stream_info",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:762",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587542432,
      "name": "xhci_free_stream_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071587542656,
      "name": "xhci_free_stream_info",
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
