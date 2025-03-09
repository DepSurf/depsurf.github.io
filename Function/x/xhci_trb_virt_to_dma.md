# Function: <code>xhci_trb_virt_to_dma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585495008,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:76",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:td_to_noop",
        "drivers/usb/host/xhci-ring.c:td_to_noop",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-ring.c:td_to_noop",
        "drivers/usb/host/xhci-ring.c:td_to_noop",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495008,
      "name": "xhci_trb_virt_to_dma.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585495856,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585900448,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:78",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890160,
      "name": "xhci_trb_virt_to_dma.part.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585890960,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586089488,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:78",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_ring_ptrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079248,
      "name": "xhci_trb_virt_to_dma.part.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586080288,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586172016,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:78",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160528,
      "name": "xhci_trb_virt_to_dma.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586162560,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586617328,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586605520,
      "name": "xhci_trb_virt_to_dma.part.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586607552,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586884272,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586873008,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587039840,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028352,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587301374,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292224,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587502574,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493168,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588371458,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588355728,
      "name": "xhci_trb_virt_to_dma",
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588401650,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588386048,
      "name": "xhci_trb_virt_to_dma",
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588267254,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:69",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588267360,
      "name": "xhci_trb_virt_to_dma",
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588918278,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:69",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588918384,
      "name": "xhci_trb_virt_to_dma",
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590349798,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:69",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590349920,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591979990,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:69",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591980128,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592401414,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:69",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592402832,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593146311,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:69",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_add_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593147776,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500643968,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500632912,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233102728,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233092288,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294064300,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294051376,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277508360,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277498828,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587208606,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587199200,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586967358,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957952,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587457134,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447728,
      "name": "xhci_trb_virt_to_dma",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t xhci_trb_virt_to_dma(struct xhci_segment * seg, union xhci_trb * trb)
```

```json
{
  "name": "xhci_trb_virt_to_dma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587564526,
      "name": "xhci_trb_virt_to_dma",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:66",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:trb_in_td",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_test_trb_in_td",
        "drivers/usb/host/xhci-mem.c:xhci_copy_ep0_dequeue_into_input_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_setup_no_streams_ep_input_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dequeue_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_enqueue_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587554992,
      "name": "xhci_trb_virt_to_dma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
