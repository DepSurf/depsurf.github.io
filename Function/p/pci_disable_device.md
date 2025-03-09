# Function: <code>pci_disable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583263968,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1586",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583263968,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574128,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1607",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574128,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583710720,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1632",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:acpi_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710720,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583751712,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1630",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751712,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584010752,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1633",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584010752,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206368,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1688",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206368,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584294176,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1861",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294176,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584488432,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1936",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584488432,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584624016,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584624016,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585306784,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2002",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306784,
      "name": "pci_disable_device",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585463408,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2138",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585463408,
      "name": "pci_disable_device",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585343536,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2168",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343536,
      "name": "pci_disable_device",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2199",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592364176,
      "name": "pci_disable_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585802640,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2259",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594226421,
      "name": "pci_disable_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586990912,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2233",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596208597,
      "name": "pci_disable_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588158240,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2271",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_clean_structure",
        "drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596733755,
      "name": "pci_disable_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588433760,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:2368",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_suspend",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597642178,
      "name": "pci_disable_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588730416,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496868072,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496868072,
      "name": "pci_disable_device",
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230145968,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/mfd/sm501.c:sm501_pci_remove",
        "drivers/mfd/sm501.c:sm501_pci_probe",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230145968,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290949472,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290949472,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275567674,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_runtime_suspend",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275567674,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584576176,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584576176,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584504336,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504336,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584574176,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574176,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void pci_disable_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584681920,
      "name": "pci_disable_device",
      "external": true,
      "loc": "drivers/pci/pci.c:1932",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pci-sysfs.c:enable_store",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/acpi/ioapic.c:pci_ioapic_remove",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_remove",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_probe",
        "drivers/virtio/virtio_pci_common.c:virtio_pci_freeze",
        "drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_enable",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681920,
      "name": "pci_disable_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
