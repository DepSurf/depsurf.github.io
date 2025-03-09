# Function: <code>pci_disable_msi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583388080,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:901",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388080,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583702496,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:915",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702496,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583840816,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:929",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840816,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881040,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:905",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881040,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584144528,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:905",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144528,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584361328,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:905",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361328,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584456480,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:904",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456480,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584653312,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:939",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653312,
      "name": "pci_disable_msi",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584789232,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789232,
      "name": "pci_disable_msi",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585481168,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481168,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585521776,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:964",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521776,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585399824,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:972",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399824,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585860000,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:880",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585860000,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587057407,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:756",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pcim_msi_release"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:pcim_msi_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054528,
      "name": "pci_disable_msi.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071587054880,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588235348,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi/api.c:51",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors",
        "drivers/pci/msi/api.c:pci_free_irq_vectors"
      ],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588234304,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588510852,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi/api.c:51",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors",
        "drivers/pci/msi/api.c:pci_free_irq_vectors"
      ],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588509808,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588809444,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi/api.c:51",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors",
        "drivers/pci/msi/api.c:pci_free_irq_vectors"
      ],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588808400,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497056392,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497056392,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230266460,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230266460,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291094208,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291094208,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275702830,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275702830,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584737984,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737984,
      "name": "pci_disable_msi",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584668752,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668752,
      "name": "pci_disable_msi",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584739392,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739392,
      "name": "pci_disable_msi",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584846960,
      "name": "pci_disable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:940",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846960,
      "name": "pci_disable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
