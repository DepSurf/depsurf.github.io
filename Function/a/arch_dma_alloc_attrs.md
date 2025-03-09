# Function: <code>arch_dma_alloc_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool arch_dma_alloc_attrs(struct device * * dev, gfp_t * gfp)
```

```json
{
  "name": "arch_dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579061424,
      "name": "arch_dma_alloc_attrs",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:132",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061424,
      "name": "arch_dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
bool arch_dma_alloc_attrs(struct device * * dev, gfp_t * gfp)
```

```json
{
  "name": "arch_dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057808,
      "name": "arch_dma_alloc_attrs",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:132",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057808,
      "name": "arch_dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
bool arch_dma_alloc_attrs(struct device * * dev, gfp_t * gfp)
```

```json
{
  "name": "arch_dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056832,
      "name": "arch_dma_alloc_attrs",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:132",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056832,
      "name": "arch_dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
bool arch_dma_alloc_attrs(struct device * * dev, gfp_t * gfp)
```

```json
{
  "name": "arch_dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049024,
      "name": "arch_dma_alloc_attrs",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:133",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/base/dma-mapping.c:dmam_alloc_attrs",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049024,
      "name": "arch_dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool arch_dma_alloc_attrs(struct device * * dev, gfp_t * gfp)
```

```json
{
  "name": "arch_dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579058016,
      "name": "arch_dma_alloc_attrs",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:137",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/base/dma-mapping.c:dmam_alloc_attrs",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
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
      "addr": 18446744071579058016,
      "name": "arch_dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool arch_dma_alloc_attrs(struct device * * dev)
```

```json
{
  "name": "arch_dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062928,
      "name": "arch_dma_alloc_attrs",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:74",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/dma/mapping.c:dmam_alloc_coherent",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/buffer.c:hcd_buffer_alloc",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_init",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_erst",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062928,
      "name": "arch_dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool arch_dma_alloc_attrs(struct device * * dev)
```

```json
{
  "name": "arch_dma_alloc_attrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579067504,
      "name": "arch_dma_alloc_attrs",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:80",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067504,
      "name": "arch_dma_alloc_attrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<code>gfp_t * gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
bool arch_dma_alloc_attrs(struct device * * dev)
```
</details>
</li>
</ul>
