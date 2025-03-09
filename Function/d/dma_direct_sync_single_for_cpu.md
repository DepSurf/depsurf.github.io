# Function: <code>dma_direct_sync_single_for_cpu</code>

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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993344,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:250",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993344,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035408,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035408,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085648,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085648,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145856,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:349",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145856,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580123686,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:66",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_cpu",
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:66",
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
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580127990,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:66",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_cpu",
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:66",
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
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580270979,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:66",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_cpu",
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:66",
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
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580442252,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:66",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_cpu",
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:66",
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
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580686460,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:67",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_cpu",
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:67",
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
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580762876,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:67",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_cpu",
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:67",
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
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580847372,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:68",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_cpu",
        "kernel/dma/mapping.c:dma_unmap_page_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "kernel/dma/direct.h:68",
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491288144,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491288144,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/firmware/tegra/ivc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:246",
      "file": "drivers/staging/emxx_udc/emxx_udc.c",
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284213536,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_for_cpu",
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284213536,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271803916,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/mmc/host/mmc_spi.c:mmc_spi_command_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271803916,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054384,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054384,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999696,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999696,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045920,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045920,
      "name": "dma_direct_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096672,
      "name": "dma_direct_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:262",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_unmap_page",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096672,
      "name": "dma_direct_sync_single_for_cpu",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
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
void dma_direct_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
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
