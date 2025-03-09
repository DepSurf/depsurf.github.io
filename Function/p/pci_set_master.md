# Function: <code>pci_set_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583268416,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:3119",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/dwc2/pci.c:dwc2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268416,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583578992,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:3429",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578832,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583716048,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:3467",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715888,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583757019,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:3605",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756864,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584016379,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:3620",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016224,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584212096,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:3804",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211936,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584301584,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4069",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301424,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584495333,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4167",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495184,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584630949,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630800,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585313916,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4234",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585313760,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585468796,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4309",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585468640,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585348540,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4341",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348384,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585807724,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4391",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807568,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586996499,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4487",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586996336,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588164687,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4430",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588164512,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588440223,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4468",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440048,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588737087,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4578",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_legacy_resume",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_resume",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588736912,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496877084,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496876920,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230154304,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/dwc2/pci.c:dwc2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230154164,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290960816,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_enable_bridge",
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290960592,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275575492,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275575334,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584583109,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582960,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584511237,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511088,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581109,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580960,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void pci_set_master(struct pci_dev * dev)
```

```json
{
  "name": "pci_set_master",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584688821,
      "name": "pci_set_master",
      "external": true,
      "loc": "drivers/pci/pci.c:4163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_bridge"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_reenable_device",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_restore",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-sff.c:ata_pci_init_one",
        "drivers/ata/ata_piix.c:piix_init_one",
        "drivers/usb/core/hcd-pci.c:resume_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584688672,
      "name": "pci_set_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
