# Function: <code>dma_direct_unmap_sg</code>

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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993856,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:298",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993856,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035904,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035904,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086144,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086144,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580147364,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:399",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_map_sg"
      ],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_unmap_memory",
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_unmap_dma_buf",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147456,
      "name": "dma_direct_unmap_sg",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127664,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:384",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_sg_attrs",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127664,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131968,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:384",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_sg_attrs",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131968,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275472,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:424",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_sg_attrs",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275472,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580447152,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:456",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_sg_attrs",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580447152,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691648,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:460",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_sg_attrs",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691648,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768256,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:459",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_sg_attrs",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768256,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:448",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_unmap_sg_attrs",
        "kernel/dma/direct.c:dma_direct_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597410379,
      "name": "dma_direct_unmap_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071580854064,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491288688,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma",
        "drivers/mmc/host/mmci.c:_mmci_dmae_prep_data",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_unprep_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491288688,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
  "name": "dma_direct_unmap_sg",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/scsi/scsi_lib_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/mtd/nand/raw/omap2.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/usb/gadget/udc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/mmc/host/mmci_stm32_sdmmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/mmc/host/omap_hsmmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_unmap_sg",
      "external": false,
      "loc": "include/linux/dma-mapping.h:241",
      "file": "drivers/mmc/host/cqhci.c",
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284214432,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_unmap_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284214432,
      "name": "dma_direct_unmap_sg",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271804444,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271804444,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054880,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054880,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000192,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000192,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046416,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046416,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_unmap_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097168,
      "name": "dma_direct_unmap_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:312",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/dma-buf/udmabuf.c:unmap_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap",
        "drivers/ata/libata-core.c:__ata_qc_complete",
        "drivers/spi/spi.c:spi_unmap_buf",
        "drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097168,
      "name": "dma_direct_unmap_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void dma_direct_unmap_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
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
