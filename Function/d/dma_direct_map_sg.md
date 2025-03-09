# Function: <code>dma_direct_map_sg</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579947232,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:149",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947232,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994320,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:337",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994320,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036352,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036352,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086592,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086592,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147232,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:438",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_map_memory",
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_map_dma_buf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_sg_setup",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147232,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128064,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:396",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_sg_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128064,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132384,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:396",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_sg_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132384,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275888,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:436",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_map_sg_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275888,
      "name": "dma_direct_map_sg",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580447616,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:468",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_map_sg_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580447616,
      "name": "dma_direct_map_sg",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692144,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:476",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_map_sg_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692144,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768752,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:475",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_map_sg_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768752,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854640,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:464",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_map_sg_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854640,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491289344,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/mmc/host/mmci.c:_mmci_dmae_prep_data",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491289344,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225295164,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev",
        "drivers/mmc/host/mmci.c:_mmci_dmae_prep_data",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data",
        "drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_pre_dma_transfer",
        "drivers/mmc/host/cqhci.c:cqhci_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225295164,
      "name": "dma_direct_map_sg",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284215232,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_sg",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284215232,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271804906,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271804906,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055328,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055328,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000640,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000640,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046864,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046864,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_map_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097616,
      "name": "dma_direct_map_sg",
      "external": true,
      "loc": "kernel/dma/direct.c:351",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/dma-buf/udmabuf.c:map_udmabuf",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097616,
      "name": "dma_direct_map_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int dma_direct_map_sg(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir, long unsigned int attrs)
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
