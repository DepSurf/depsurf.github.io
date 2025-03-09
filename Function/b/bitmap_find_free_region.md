# Function: <code>bitmap_find_free_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011408,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1012",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011408,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301936,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1014",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301936,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420976,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1056",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420976,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583442112,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1062",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442112,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622048,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1058",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622048,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583839312,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1055",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839312,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583924000,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1050",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924000,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101776,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1078",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:__dma_alloc_from_coherent",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101776,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224560,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224560,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584632176,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1173",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel/irq_remapping.c:alloc_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632176,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584751216,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1173",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751216,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584779648,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1184",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779648,
      "name": "bitmap_find_free_region",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1315",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592322966,
      "name": "bitmap_find_free_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585208400,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1332",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594126811,
      "name": "bitmap_find_free_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586044464,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1313",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596113854,
      "name": "bitmap_find_free_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587027376,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1313",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596638959,
      "name": "bitmap_find_free_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587282480,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589009268,
      "name": "bitmap_find_free_region",
      "external": false,
      "loc": "include/linux/bitmap.h:547",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589021615,
      "name": "bitmap_find_free_region",
      "external": false,
      "loc": "include/linux/bitmap.h:547",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590832207,
      "name": "bitmap_find_free_region",
      "external": false,
      "loc": "include/linux/bitmap.h:547",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:alloc_irte"
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496098392,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:__dma_alloc_from_coherent",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_alloc",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496098392,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229425300,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:__dma_alloc_from_coherent",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229425300,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290343040,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:__dma_alloc_from_coherent",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290343040,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275166550,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:__dma_alloc_from_coherent",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275166550,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193296,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193296,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128512,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128512,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584177056,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177056,
      "name": "bitmap_find_free_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
```

```json
{
  "name": "bitmap_find_free_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281392,
      "name": "bitmap_find_free_region",
      "external": true,
      "loc": "lib/bitmap.c:1098",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281392,
      "name": "bitmap_find_free_region",
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int bitmap_find_free_region(long unsigned int * bitmap, unsigned int bits, int order)
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
