# Function: <code>xhci_get_slot_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585480016,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:547",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480016,
      "name": "xhci_get_slot_ctx",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585879765,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:559",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585875936,
      "name": "xhci_get_slot_ctx",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586068613,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:559",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586064784,
      "name": "xhci_get_slot_ctx",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586150597,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:513",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586146960,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586596357,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:500",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592000,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586859157,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586854736,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587015717,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011184,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587278869,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587274384,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587479509,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587474960,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588343205,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_addr_dev",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_disable_slot",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337760,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588374789,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:513",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_disable_slot",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369408,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588257157,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:513",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251920,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588907541,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:513",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900976,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590337013,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:512",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590330160,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591965365,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:512",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591957840,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592386549,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592378976,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593130021,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:515",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593122416,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500616580,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500611448,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233077100,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233072464,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294031032,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294025184,
      "name": "xhci_get_slot_ctx",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277484870,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277480444,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587185541,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587180992,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586944293,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586939744,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587434069,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587429520,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct xhci_slot_ctx * xhci_get_slot_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx)
```

```json
{
  "name": "xhci_get_slot_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587541029,
      "name": "xhci_get_slot_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:504",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_slot_copy",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-dbg.c:xhci_get_slot_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587536432,
      "name": "xhci_get_slot_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
