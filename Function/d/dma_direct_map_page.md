# Function: <code>dma_direct_map_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947072,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:138",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947072,
      "name": "dma_direct_map_page",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993968,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:318",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993968,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036112,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036112,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086352,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086352,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146352,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:412",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-ring.c:xhci_align_td",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146352,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580122512,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:83",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_page_attrs"
      ]
    },
    {
      "addr": 18446744071580128287,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:83",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_map_sg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122512,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580126800,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:83",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_page_attrs"
      ]
    },
    {
      "addr": 18446744071580132623,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:83",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_map_sg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126800,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Transformation ❓</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:83",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_page_attrs"
      ]
    },
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:83",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269728,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    },
    {
      "addr": 18446744071592149760,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071580271488,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    },
    {
      "addr": 18446744071592149824,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Transformation ❓</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:83",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_page_attrs"
      ]
    },
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:83",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440720,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071593922464,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580442800,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071593922529,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Transformation ❓</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:84",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_page_attrs"
      ]
    },
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:84",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684800,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071595992869,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580686928,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071595992934,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Transformation ❓</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:84",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_page_attrs"
      ]
    },
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:84",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761216,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071596511129,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580763536,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071596511194,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Transformation ❓</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:85",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_page_attrs"
      ]
    },
    {
      "addr": 0,
      "name": "dma_direct_map_page",
      "external": false,
      "loc": "kernel/dma/direct.h:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846368,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
    },
    {
      "addr": 18446744071597410002,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580849280,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
    },
    {
      "addr": 18446744071597410183,
      "name": "dma_direct_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491289008,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/soc/fsl/qbman/qman.c:qman_init_fq",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/firmware/qcom_scm-64.c:qcom_scm_call",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491289008,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225294816,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages",
        "drivers/iommu/omap-iommu.c:omap_iommu_attach_dev",
        "drivers/iommu/omap-iommu.c:iopte_alloc",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_map",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_map",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/firmware/qcom_scm-32.c:qcom_scm_call",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225294816,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284214896,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_page",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe",
        "drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284214896,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271804706,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271804706,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055088,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/nvme/host/pci.c:nvme_queue_rq",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055088,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000400,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/nvme/host/pci.c:nvme_queue_rq",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000400,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046624,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046624,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097376,
      "name": "dma_direct_map_page",
      "external": true,
      "loc": "kernel/dma/direct.c:332",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097376,
      "name": "dma_direct_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
dma_addr_t dma_direct_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
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
