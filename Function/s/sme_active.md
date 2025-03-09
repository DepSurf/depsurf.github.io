# Function: <code>sme_active</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602725264,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:404",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel",
        "lib/swiotlb.c:swiotlb_tbl_map_single",
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
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
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
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
      "addr": 18446744071579370128,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602896740,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:338",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
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
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_detect",
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
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383648,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604694049,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:338",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "fs/proc/vmcore.c:read_vmcore",
        "fs/proc/vmcore.c:elfcorehdr_read_notes",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_detect",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411504,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604794067,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:343",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_detect",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427264,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604819790,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:343",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_detect",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430432,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609157955,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:343",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd/init.c:amd_iommu_detect",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455952,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579452620,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:376",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd/init.c:amd_iommu_detect",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452576,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579455036,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:380",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd/init.c:amd_iommu_detect",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454992,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520444,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:381",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd/init.c:amd_iommu_detect",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520400,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604733670,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:343",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_detect",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426272,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604701291,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:343",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_detect",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355376,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604811237,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:343",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_detect",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426192,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool sme_active()
```

```json
{
  "name": "sme_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604823947,
      "name": "sme_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:343",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_detect",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435376,
      "name": "sme_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool sme_active()
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool sme_active()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool sme_active()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool sme_active()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool sme_active()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool sme_active()
```
</details>
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
