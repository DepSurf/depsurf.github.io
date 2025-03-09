# Function: <code>dma_free_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580784922,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584127232,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584180789,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584471962,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_coherent_release",
        "drivers/base/dma-mapping.c:dmam_noncoherent_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585233526,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309073,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326399,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585352867,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585403525,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585437539,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585485699,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:267",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
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
  "name": "dma_free_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580908272,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584150157,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584463204,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519886,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584817250,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_noncoherent_release",
        "drivers/base/dma-mapping.c:dmam_coherent_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585626950,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585702032,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585747231,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585799573,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585833427,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585886899,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:426",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info"
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
  "name": "dma_free_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580976288,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584330717,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584645414,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584701966,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585010514,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_noncoherent_release",
        "drivers/base/dma-mapping.c:dmam_coherent_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585814566,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585890815,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585937071,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585991189,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586022179,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586075994,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:478",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_stream_info"
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
  "name": "dma_free_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581023081,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583902504,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410729,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584728457,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584783347,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585095925,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585901483,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973482,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586019732,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586074781,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586105407,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586157697,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:521",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
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
  "name": "dma_free_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581132537,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584165672,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584818185,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585142908,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585203484,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585521686,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dmam_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586342251,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417261,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586463940,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586519239,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549807,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586602872,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586655378,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:530",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
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
  "name": "dma_free_attrs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579945685,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dmam_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275506,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584383671,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048650,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585377078,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585439769,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586599791,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/usb/core/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/buffer.c:hcd_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586679472,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586727476,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780044,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586814060,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586867979,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586918961,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587091991,
      "name": "dma_free_attrs",
      "external": false,
      "loc": "include/linux/dma-mapping.h:534",
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991888,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:276",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991888,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:293",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035208,
      "name": "dma_free_attrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580033696,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084496,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084496,
      "name": "dma_free_attrs",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144288,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:292",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144288,
      "name": "dma_free_attrs",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121472,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:451",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:release_uhci",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ring_free",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121472,
      "name": "dma_free_attrs",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580125040,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:453",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ring_free",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125040,
      "name": "dma_free_attrs",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267984,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:518",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_free_coherent",
        "kernel/dma/mapping.c:dmam_release",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ring_free",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267984,
      "name": "dma_free_attrs",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438528,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:512",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_free_coherent",
        "kernel/dma/mapping.c:dmam_release",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ring_free",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438528,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682112,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:527",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_free_coherent",
        "kernel/dma/mapping.c:dmam_release",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ring_free",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682112,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758640,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:531",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_free_coherent",
        "kernel/dma/mapping.c:dmam_release",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_free_pages",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ring_free",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758640,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843760,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:531",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_free_coherent",
        "kernel/dma/mapping.c:dmam_release",
        "mm/dmapool.c:dma_pool_destroy",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:free_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_free_pages",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_interrupter",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-mem.c:scratchpad_alloc",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843760,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491285632,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_of_dma_remove",
        "drivers/video/fbdev/mx3fb.c:mx3fb_unmap_video_memory",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_remove",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_free",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_free",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/firmware/raspberrypi.c:rpi_firmware_property_list",
        "drivers/firmware/qcom_scm.c:qcom_scm_assign_mem",
        "drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491285632,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225292804,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_of_dma_remove",
        "drivers/video/fbdev/mx3fb.c:mx3fb_unmap_video_memory",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_desc_pool_destroy",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/mmc/host/sdhci.c:sdhci_remove_host",
        "drivers/mmc/host/sdhci.c:sdhci_cleanup_host",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/firmware/qcom_scm.c:qcom_scm_assign_mem",
        "drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image",
        "drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs",
        "drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs",
        "drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show",
        "drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show",
        "drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_remove",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout",
        "sound/soc/fsl/imx-pcm-fiq.c:imx_pcm_fiq_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225292804,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284211552,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_free_coherent",
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284211552,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271802372,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271802372,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053232,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_alloc_host_mem",
        "drivers/nvme/host/pci.c:nvme_alloc_host_mem",
        "drivers/nvme/host/pci.c:nvme_free_host_mem",
        "drivers/nvme/host/pci.c:nvme_free_host_mem",
        "drivers/nvme/host/pci.c:nvme_alloc_queue",
        "drivers/nvme/host/pci.c:nvme_free_queue",
        "drivers/nvme/host/pci.c:nvme_free_queue",
        "drivers/nvme/host/pci.c:nvme_dbbuf_dma_free",
        "drivers/nvme/host/pci.c:nvme_dbbuf_dma_free",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053232,
      "name": "dma_free_attrs",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998544,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_alloc_host_mem",
        "drivers/nvme/host/pci.c:nvme_alloc_host_mem",
        "drivers/nvme/host/pci.c:nvme_free_host_mem",
        "drivers/nvme/host/pci.c:nvme_free_host_mem",
        "drivers/nvme/host/pci.c:nvme_alloc_queue",
        "drivers/nvme/host/pci.c:nvme_free_queue",
        "drivers/nvme/host/pci.c:nvme_free_queue",
        "drivers/nvme/host/pci.c:nvme_dbbuf_dma_free",
        "drivers/nvme/host/pci.c:nvme_dbbuf_dma_free",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998544,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044768,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044768,
      "name": "dma_free_attrs",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
```

```json
{
  "name": "dma_free_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095520,
      "name": "dma_free_attrs",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_release",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/xen/grant-table.c:gnttab_dma_free_pages",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_free_erst",
        "drivers/remoteproc/remoteproc_core.c:rproc_release_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095520,
      "name": "dma_free_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void dma_free_attrs(struct device * dev, size_t size, void * cpu_addr, dma_addr_t dma_handle, long unsigned int attrs)
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
