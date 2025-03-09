# Function: <code>dma_direct_unmap_page</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993728,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:285",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993728,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035776,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page",
        "drivers/iommu/intel-iommu.c:intel_unmap_page",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035776,
      "name": "dma_direct_unmap_page",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086016,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page",
        "drivers/iommu/intel-iommu.c:intel_unmap_page",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086016,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580146224,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:386",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "net/core/page_pool.c:page_pool_release_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146224,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580123083,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:108",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580127742,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:108",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_unmap_sg"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580127371,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:108",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580132046,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:108",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_unmap_sg"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580270363,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:108",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580275549,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:108",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_unmap_sg"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580441525,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:108",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447229,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:108",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_unmap_sg"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580685701,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:114",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580691765,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:114",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_unmap_sg"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580762117,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:115",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580768373,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:115",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_unmap_sg"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580848175,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:116",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854185,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "kernel/dma/direct.h:116",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_unmap_sg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491288520,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_free",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/tty/serial/msm_serial.c:msm_handle_tx",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_tx_dma",
        "drivers/tty/serial/msm_serial.c:msm_stop_dma",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/freescale/fec_main.c:fec_restart",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "drivers/firmware/qcom_scm-64.c:qcom_scm_call",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491288520,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/iommu/tegra-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/usb/gadget/udc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/i2c/busses/i2c-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/firmware/tegra/ivc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "drivers/staging/emxx_udc/emxx_udc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_page",
      "external": false,
      "loc": "include/linux/dma-mapping.h:237",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284214192,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_unmap_page",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284214192,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271804308,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "drivers/mmc/host/mmc_spi.c:mmc_spi_remove",
        "drivers/mmc/host/mmc_spi.c:mmc_spi_remove",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271804308,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054752,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page",
        "drivers/iommu/intel-iommu.c:intel_unmap_page",
        "drivers/nvme/host/pci.c:nvme_pci_complete_rq",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054752,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000064,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page",
        "drivers/iommu/intel-iommu.c:intel_unmap_page",
        "drivers/nvme/host/pci.c:nvme_pci_complete_rq",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000064,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046288,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page",
        "drivers/iommu/intel-iommu.c:intel_unmap_page",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_check_cmd_completion",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046288,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097040,
      "name": "dma_direct_unmap_page",
      "external": true,
      "loc": "kernel/dma/direct.c:299",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "mm/hmm.c:hmm_range_dma_unmap",
        "mm/hmm.c:hmm_range_dma_map",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/virtio/virtio_ring.c:detach_buf_packed",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma",
        "drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page",
        "drivers/iommu/intel-iommu.c:intel_unmap_page",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback",
        "net/core/page_pool.c:__page_pool_clean_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097040,
      "name": "dma_direct_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void dma_direct_unmap_page(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
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
