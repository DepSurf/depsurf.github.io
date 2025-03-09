# Function: <code>dma_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061536,
      "name": "dma_supported",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:215",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061536,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579057920,
      "name": "dma_supported",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:215",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057920,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579056944,
      "name": "dma_supported",
      "external": true,
      "loc": "arch/x86/kernel/pci-dma.c:215",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056944,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583900760,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420881,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584424999,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431069,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830429,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585648231,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947639,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973930,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586054916,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586056333,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084185,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586124032,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
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
  "name": "dma_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584163992,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584828467,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584832792,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839003,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585252287,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586080133,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586390775,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417707,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586499300,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586500877,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586528630,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586566936,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:577",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
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
  "name": "dma_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585058560,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585063168,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069707,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489039,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586328165,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586651160,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586679931,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763753,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765116,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586792390,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586831673,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587089869,
      "name": "dma_supported",
      "external": false,
      "loc": "include/linux/dma-mapping.h:581",
      "file": "drivers/i2c/busses/i2c-amd-pci-mp2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992016,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:309",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992016,
      "name": "dma_supported",
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580033904,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:326",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033904,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084608,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084608,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580144901,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:319",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144416,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580123829,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:558",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122016,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580128213,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:648",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126176,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580271205,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:713",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269296,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580442517,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:707",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440144,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580686629,
      "name": "dma_supported",
      "external": false,
      "loc": "kernel/dma/mapping.c:726",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
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
  "name": "dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580763045,
      "name": "dma_supported",
      "external": false,
      "loc": "kernel/dma/mapping.c:730",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
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
  "name": "dma_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580847141,
      "name": "dma_supported",
      "external": false,
      "loc": "kernel/dma/mapping.c:730",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491285912,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491285912,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225293076,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225293076,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284212048,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284212048,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271802654,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271802654,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053344,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053344,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998656,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998656,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044880,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044880,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int dma_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095632,
      "name": "dma_supported",
      "external": true,
      "loc": "kernel/dma/mapping.c:348",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095632,
      "name": "dma_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int dma_supported(struct device * dev, u64 mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int dma_supported(struct device * dev, u64 mask)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int dma_supported(struct device * dev, u64 mask)
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
