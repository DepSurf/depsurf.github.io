# Function: <code>dma_alloc_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580784256,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584126481,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584182106,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584471727,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585233227,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310648,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326654,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585364781,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585404115,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585440084,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585485332,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:245",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580907580,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584150542,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584462260,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584521226,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584816371,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585626644,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703666,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585761338,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585800185,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585835956,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585884683,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:404",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580975596,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331102,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584644446,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584703642,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585010147,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585814260,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585892391,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585951082,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585991801,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586024692,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586073821,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:456",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581022432,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902696,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584411070,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584727527,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584785014,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585095086,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_alloc_attrs",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585901185,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585975172,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586035004,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586075325,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586107828,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586155571,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581131872,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584165864,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584818526,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585141997,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205226,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585521006,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_alloc_attrs",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586341953,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586418945,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586479212,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586519773,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586552216,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586600962,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586656072,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579944878,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/dma/mapping.c:dmam_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274788,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584383896,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048929,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585376131,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585441697,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:alloc_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586599448,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586681243,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586743384,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780591,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586815812,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586863945,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586919665,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587091774,
      "name": "dma_alloc_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:508",
      "file": "drivers/i2c/busses/i2c-amd-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991488,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:247",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991488,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580033312,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:267",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033312,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084224,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084224,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144016,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:266",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:pool_alloc_page",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144016,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121216,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:425",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:pool_alloc_page",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121216,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124784,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:427",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124784,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267712,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:492",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267712,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438208,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:486",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438208,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681696,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:493",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681696,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758208,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:497",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc_pages",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758208,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843328,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:497",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc_pages",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843328,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491285208,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/firmware/raspberrypi.c:rpi_firmware_property_list",
        "drivers/firmware/qcom_scm.c:qcom_scm_assign_mem",
        "drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491285208,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225292332,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/video/fbdev/mx3fb.c:__set_par",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_probe",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/firmware/qcom_scm.c:qcom_scm_assign_mem",
        "drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image",
        "drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_queue",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout",
        "sound/core/memalloc.c:snd_dma_alloc_pages",
        "sound/soc/fsl/imx-pcm-fiq.c:imx_pcm_preallocate_dma_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225292332,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284210992,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284210992,
      "name": "dma_alloc_attrs",
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271802068,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271802068,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052960,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_alloc_host_mem",
        "drivers/nvme/host/pci.c:nvme_alloc_host_mem",
        "drivers/nvme/host/pci.c:nvme_alloc_queue",
        "drivers/nvme/host/pci.c:nvme_alloc_queue",
        "drivers/nvme/host/pci.c:nvme_alloc_queue",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052960,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998272,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_alloc_host_mem",
        "drivers/nvme/host/pci.c:nvme_alloc_host_mem",
        "drivers/nvme/host/pci.c:nvme_alloc_queue",
        "drivers/nvme/host/pci.c:nvme_alloc_queue",
        "drivers/nvme/host/pci.c:nvme_alloc_queue",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998272,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044496,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044496,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```

```json
{
  "name": "dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095248,
      "name": "dma_alloc_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:295",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095248,
      "name": "dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * dma_alloc_attrs(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t flag, long unsigned int attrs)
```
</details>
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
