# Function: <code>dma_pool_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784064,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:321",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784064,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907392,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:320",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907392,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580975408,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:320",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975408,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581022240,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:320",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022240,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581131680,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:320",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131680,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274608,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:320",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274608,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357568,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:320",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357568,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581467936,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467936,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531984,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531984,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740160,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:317",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:itd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740160,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788960,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:314",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:itd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788960,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581816432,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:315",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:itd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816432,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102672,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:314",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:itd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102672,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542992,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:314",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:itd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542992,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583058784,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:314",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:itd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058784,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269088,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:404",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:itd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269088,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583504960,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:404",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:itd_urb_transaction",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_control",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583504960,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492962472,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_create_cb_chain",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492962472,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226742292,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_fill_llis_for_desc",
        "drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_td",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226742292,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286376720,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_td",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286376720,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272873176,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ehci-hcd.c:ehci_qtd_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_td",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272873176,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500720,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/lightnvm.c:nvme_nvm_dev_dma_alloc",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500720,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442944,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442944,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492032,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492032,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void * dma_pool_alloc(struct dma_pool * pool, gfp_t mem_flags, dma_addr_t * handle)
```

```json
{
  "name": "dma_pool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557056,
      "name": "dma_pool_alloc",
      "external": true,
      "loc": "mm/dmapool.c:319",
      "file": "mm/dmapool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:ehci_qh_alloc",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx",
        "drivers/usb/host/xhci-mem.c:xhci_segment_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557056,
      "name": "dma_pool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
