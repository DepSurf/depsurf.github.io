# Function: <code>xhci_alloc_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585484112,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1724",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585484112,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585879872,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1740",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585879872,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068720,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1773",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068720,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586150688,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1715",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586150688,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586596448,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1717",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596448,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586859248,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1732",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859248,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587015808,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1732",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015808,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587278960,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1732",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587278960,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587479600,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479600,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588343296,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343296,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588374880,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1746",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588374880,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588257248,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1733",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588257248,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588907632,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1733",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907632,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590337120,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1724",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590337120,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591965488,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1733",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591965488,
      "name": "xhci_alloc_command",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592386672,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1713",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592386672,
      "name": "xhci_alloc_command",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593130144,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1721",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593130144,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500616712,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500616712,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233077208,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233077208,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294031184,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294031184,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277484964,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277484964,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587185632,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185632,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944384,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944384,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587434160,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587434160,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct xhci_command * xhci_alloc_command(struct xhci_hcd * xhci, bool allocate_completion, gfp_t mem_flags)
```

```json
{
  "name": "xhci_alloc_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587541120,
      "name": "xhci_alloc_command",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:1738",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541120,
      "name": "xhci_alloc_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool allocate_in_ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, allocate_in_ctx, allocate_completion, mem_flags</code> ➡️ <code>xhci, allocate_completion, mem_flags</code>
</li>
</ul>
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
