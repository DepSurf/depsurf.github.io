# Function: <code>early_ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_ioremap",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_map",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595155632,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:209",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_map",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595329179,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:209",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_map",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595577357,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596504940,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:209",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_map",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596504940,
      "name": "early_ioremap",
      "section": ".init.text",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602832365,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_map",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602832365,
      "name": "early_ioremap",
      "section": ".init.text",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603005678,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_map",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603005678,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604804306,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_map",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604804306,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604907706,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604907706,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604941552,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604941552,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609255388,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609255388,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612321697,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612321697,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614461909,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614461909,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615407424,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:212",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615407424,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617199565,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:213",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617199565,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627899184,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:213",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627899184,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619662240,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:211",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619662240,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621968288,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:211",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:early_pci_serial_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621968288,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510981908,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510981908,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243461256,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243461256,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604847012,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604847012,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604816064,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604816064,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604924196,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604924196,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604945723,
      "name": "early_ioremap",
      "external": true,
      "loc": "mm/early_ioremap.c:217",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/early_printk.c:setup_early_printk",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604945723,
      "name": "early_ioremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * early_ioremap(resource_size_t phys_addr, long unsigned int size)
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
