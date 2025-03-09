# Function: <code>xhci_get_ep_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585480064,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:557",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480064,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585879670,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:569",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585875984,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586068518,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:569",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586064832,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586150502,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:523",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147008,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586596262,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:510",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592048,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586859029,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586854784,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587015589,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011232,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587278741,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587274432,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587479381,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587475008,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588343077,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337808,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588374675,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:523",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369456,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588257043,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:523",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588244368,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588907427,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:523",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892592,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590336879,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:522",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590321232,
      "name": "xhci_get_ep_ctx",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591965215,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:522",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591947824,
      "name": "xhci_get_ep_ctx",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592386399,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci.c:xhci_check_maxpacket",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592370352,
      "name": "xhci_get_ep_ctx",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593129871,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:525",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_zero_in_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593111984,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500616400,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500611528,
      "name": "xhci_get_ep_ctx",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233076940,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233072528,
      "name": "xhci_get_ep_ctx",
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294030856,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294025264,
      "name": "xhci_get_ep_ctx",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277484708,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277480512,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587185413,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587181040,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586944165,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586939792,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587433941,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587429568,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct xhci_ep_ctx * xhci_get_ep_ctx(struct xhci_hcd * xhci, struct xhci_container_ctx * ctx, unsigned int ep_index)
```

```json
{
  "name": "xhci_get_ep_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587540901,
      "name": "xhci_get_ep_ctx",
      "external": true,
      "loc": "drivers/usb/host/xhci-mem.c:514",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_copy",
        "drivers/usb/host/xhci-mem.c:xhci_update_bw_info",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_zero",
        "drivers/usb/host/xhci-mem.c:xhci_endpoint_init",
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_intr_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587536480,
      "name": "xhci_get_ep_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
