# Function: <code>xhci_free_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585484480,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1768",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585484480,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585880240,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1784",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585880240,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586069088,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1817",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586069088,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586151008,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1756",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151008,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586596752,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1758",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596752,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586859600,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1782",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859600,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587016224,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1782",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587016224,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587279328,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1782",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587279328,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587479968,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479968,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588345048,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588344592,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588376632,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1796",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376176,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588259000,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1783",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258544,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588909624,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1783",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909168,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590338229,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1774",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590338640,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591966671,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1783",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591967152,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592387839,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1763",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592388304,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593131403,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1773",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593131872,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500617112,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500617112,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233077528,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233077528,
      "name": "xhci_free_command",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294031712,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294031712,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277485296,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277485296,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587186000,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587186000,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944752,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944752,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587434528,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434528,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void xhci_free_command(struct xhci_hcd * xhci, struct xhci_command * command)
```

```json
{
  "name": "xhci_free_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587541488,
      "name": "xhci_free_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1788",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541488,
      "name": "xhci_free_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
