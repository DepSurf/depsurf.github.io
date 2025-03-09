# Function: <code>xhci_free_virt_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585485824,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:913",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485824,
      "name": "xhci_free_virt_device.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071585486208,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585883212,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:928",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881616,
      "name": "xhci_free_virt_device.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071585882000,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586071665,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:928",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070464,
      "name": "xhci_free_virt_device.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071586070848,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586153503,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:882",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152320,
      "name": "xhci_free_virt_device.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071586152736,
      "name": "xhci_free_virt_device",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586598553,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:869",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598048,
      "name": "xhci_free_virt_device.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071586598448,
      "name": "xhci_free_virt_device",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586861008,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586861008,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587017392,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017392,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587285189,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587280528,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587485888,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587481168,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348206,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588338544,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:886",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_disable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591565270,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588370192,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:869",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591508097,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588252576,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:869",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592609477,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588901744,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 811
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:860",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594492485,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071590331008,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 847
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591958832,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:865",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591958832,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 937
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592379968,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:847",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592379968,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 937
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593123424,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:858",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-hub.c:xhci_enter_test_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593123424,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 937
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500618376,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500618376,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233078680,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233078680,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294033344,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294033344,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277486398,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277486398,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587191920,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587187200,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950672,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586945952,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440448,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587435728,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void xhci_free_virt_device(struct xhci_hcd * xhci, int slot_id)
```

```json
{
  "name": "xhci_free_virt_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_free_virt_device",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:877",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587547424,
      "name": "xhci_free_virt_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587542688,
      "name": "xhci_free_virt_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
