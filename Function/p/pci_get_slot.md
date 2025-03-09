# Function: <code>pci_get_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279760,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:185",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/tty/serial/8250/8250_pci.c:byt_serial_setup",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279760,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583590832,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/access.c:pci_vpd_f0_set_size",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/tty/serial/8250/8250_pci.c:byt_serial_setup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590832,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727968,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/access.c:pci_vpd_f0_set_size",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727968,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583768880,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:193",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/access.c:pci_vpd_f0_set_size",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768880,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028704,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:193",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/access.c:pci_vpd_f0_set_size",
        "drivers/pci/access.c:pci_vpd_f0_write",
        "drivers/pci/access.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/quirks.c:quirk_f0_vpd_link",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028704,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225968,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:194",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225968,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315616,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:194",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315616,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:190",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511721,
      "name": "pci_get_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584510576,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584646608,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646608,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585329584,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:195",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_core.c:init_slots",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:uli_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329584,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585482816,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:195",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_core.c:init_slots",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:uli_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482816,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585362608,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:194",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362608,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585821984,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:194",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/vpd.c:pci_vpd_size",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821984,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587012384,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:194",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587012384,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588182432,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:194",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/tty/serial/8250/8250_mid.c:tng_setup",
        "drivers/tty/serial/8250/8250_mid.c:pnw_setup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182432,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588458432,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:194",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/tty/serial/8250/8250_mid.c:tng_setup",
        "drivers/tty/serial/8250/8250_mid.c:pnw_setup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458432,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588755520,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:194",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_write_vpd_any",
        "drivers/pci/vpd.c:vpd_write",
        "drivers/pci/vpd.c:vpd_read",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:nv_ht_enable_msi_mapping",
        "drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/tty/serial/8250/8250_mid.c:tng_setup",
        "drivers/tty/serial/8250/8250_mid.c:pnw_setup",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755520,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496892664,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496892664,
      "name": "pci_get_slot",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230170412,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230170412,
      "name": "pci_get_slot",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290980560,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci_of_scan.c:__of_scan_bus",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290980560,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275585516,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275585516,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597088,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597088,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526896,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526896,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596768,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596768,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pci_dev * pci_get_slot(struct pci_bus * bus, unsigned int devfn)
```

```json
{
  "name": "pci_get_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584704464,
      "name": "pci_get_slot",
      "external": true,
      "loc": "drivers/pci/search.c:189",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node",
        "drivers/pci/vpd.c:quirk_f0_vpd_link",
        "drivers/pci/vpd.c:pci_vpd_f0_set_size",
        "drivers/pci/vpd.c:pci_vpd_f0_write",
        "drivers/pci/vpd.c:pci_vpd_f0_read",
        "drivers/pci/quirks.c:quirk_amd_780_apc_msi",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:sriov_enable",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/ata/pata_sis.c:sis_init_one",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704464,
      "name": "pci_get_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
