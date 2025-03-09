# Function: <code>xhci_alloc_command_with_ctx</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586859488,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1758",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859488,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587016112,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1758",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587016112,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587279200,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1758",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587279200,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587479840,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479840,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588343536,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343536,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588375120,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1772",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375120,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588257488,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1759",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588257488,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588908016,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1759",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588908016,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590337520,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1750",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590337520,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591965952,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1759",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591965952,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592387136,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1739",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592387136,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593130672,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1749",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593130672,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500616936,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500616936,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233077396,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233077396,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294031488,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294031488,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277485148,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277485148,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587185872,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185872,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944624,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944624,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587434400,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434400,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command_with_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587541360,
      "name": "xhci_alloc_command_with_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1764",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541360,
      "name": "xhci_alloc_command_with_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct xhci_command * xhci_alloc_command_with_ctx(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```
</details>
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
