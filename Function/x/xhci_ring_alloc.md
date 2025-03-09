# Function: <code>xhci_ring_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476656,
      "name": "xhci_ring_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476656,
      "name": "xhci_ring_alloc.constprop.33",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874752,
      "name": "xhci_ring_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:372",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874752,
      "name": "xhci_ring_alloc.constprop.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586063600,
      "name": "xhci_ring_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:372",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586063600,
      "name": "xhci_ring_alloc.constprop.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586145968,
      "name": "xhci_ring_alloc",
      "external": false,
      "loc": "drivers/usb/host/xhci-mem.c:371",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145968,
      "name": "xhci_ring_alloc.constprop.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586590800,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:360",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590800,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586853520,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853520,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009920,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009920,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587273120,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587273120,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587473696,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587473696,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588336432,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588336432,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588367808,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:371",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588367808,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588250336,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:371",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588250336,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588899136,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:371",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588899136,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590328352,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:371",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328352,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591955920,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:371",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591955920,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592377104,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:371",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592377104,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593119520,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:381",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593119520,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500609944,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500609944,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233071096,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233071096,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294023312,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294023312,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277479236,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277479236,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587179728,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587179728,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938480,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938480,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587428256,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587428256,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
```

```json
{
  "name": "xhci_ring_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587535120,
      "name": "xhci_ring_alloc",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:362",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587535120,
      "name": "xhci_ring_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
struct xhci_ring * xhci_ring_alloc(struct xhci_hcd * xhci, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags)
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
