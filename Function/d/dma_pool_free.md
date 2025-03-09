# Function: <code>dma_pool_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783632,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:412",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783632,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906960,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:411",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906960,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974976,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:411",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974976,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021824,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:411",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021824,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581131264,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:411",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131264,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:411",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275651,
      "name": "dma_pool_free.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581274208,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:411",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358605,
      "name": "dma_pool_free.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581357376,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469197,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581468416,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533245,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581532464,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:408",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741203,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581740432,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:404",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591332126,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071581788752,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:405",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591274797,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071581816224,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:404",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592210614,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071582102464,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:404",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593988814,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071582542768,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583058448,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:404",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058448,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270592,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:450",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270592,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583506512,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:450",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:qh_destroy",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506512,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492962088,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_free_cb_chain",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492962088,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226742756,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_free_txd",
        "drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg",
        "drivers/dma/ti/omap-dma.c:omap_dma_desc_free",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_free",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226742756,
      "name": "dma_pool_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286377408,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_free",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286377408,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272873600,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_free",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272873600,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/lightnvm.c:nvme_nvm_dev_dma_free",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501981,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581501200,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444205,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581443424,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493293,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581492512,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void dma_pool_free(struct dma_pool * pool, void * vaddr, dma_addr_t dma)
```

```json
{
  "name": "dma_pool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_pool_free",
      "external": true,
      "loc": "mm/dmapool.c:410",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:qh_completions",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/usb/host/uhci-hcd.c:uhci_free_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_free_td",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558301,
      "name": "dma_pool_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581557520,
      "name": "dma_pool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
