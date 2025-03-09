# Function: <code>dma_direct_sync_single_for_device</code>

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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993264,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:215",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993264,
      "name": "dma_direct_sync_single_for_device",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035328,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035328,
      "name": "dma_direct_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085568,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085568,
      "name": "dma_direct_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145776,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_fill_host_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145776,
      "name": "dma_direct_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580123494,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "kernel/dma/direct.h:54",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_device"
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
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580127798,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "kernel/dma/direct.h:54",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_device"
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
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580270787,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "kernel/dma/direct.h:54",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_device"
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
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580441996,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "kernel/dma/direct.h:54",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_device"
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
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580686191,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "kernel/dma/direct.h:55",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_device"
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
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580762607,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "kernel/dma/direct.h:55",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_device"
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
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580847711,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "kernel/dma/direct.h:56",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_sync_single_for_device"
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491287728,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491287728,
      "name": "dma_direct_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/iommu/tegra-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
      "file": "drivers/firmware/tegra/ivc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:215",
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284213424,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_for_device",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284213424,
      "name": "dma_direct_sync_single_for_device",
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271803816,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "drivers/mmc/host/mmc_spi.c:mmc_spi_command_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271803816,
      "name": "dma_direct_sync_single_for_device",
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054304,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054304,
      "name": "dma_direct_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999616,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999616,
      "name": "dma_direct_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045840,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045840,
      "name": "dma_direct_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096592,
      "name": "dma_direct_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:225",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096592,
      "name": "dma_direct_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
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
void dma_direct_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
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
