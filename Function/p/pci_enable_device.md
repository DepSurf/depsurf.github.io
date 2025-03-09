# Function: <code>pci_enable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583268976,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1398",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:resume_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268976,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583579505,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1419",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579408,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583716561,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1444",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583716464,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583757521,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1442",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757424,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584016881,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1445",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016784,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584212593,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1496",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212496,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584302081,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1669",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301984,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584495825,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1743",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495728,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584631441,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631344,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585314481,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1809",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314384,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585469361,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1945",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585469264,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585349057,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1975",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348960,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585808289,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2006",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808192,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586997104,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2071",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586996992,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588165392,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2045",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588165264,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588440928,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2083",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440800,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588737792,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2180",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_resume",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588737664,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496877760,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496877616,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230154884,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/mfd/sm501.c:sm501_pci_probe",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230154772,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290961616,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_enable_bridge",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/video/fbdev/gxt4500.c:gxt4500_probe",
        "drivers/video/fbdev/offb.c:offb_init_nodriver",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290961440,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275576014,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275575888,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584583601,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583504,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584511729,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511632,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581601,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_resume",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581504,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int pci_enable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584689313,
      "name": "pci_enable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1739",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcim_enable_device"
      ],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe",
        "drivers/pci/pci.c:pci_enable_bridge",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689216,
      "name": "pci_enable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
