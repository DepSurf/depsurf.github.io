# Function: <code>early_iounmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595155316,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:160",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_unmap",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595155316,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595328870,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:160",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_unmap",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595328870,
      "name": "early_iounmap",
      "section": ".init.text",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595577048,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:160",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_unmap",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595577048,
      "name": "early_iounmap",
      "section": ".init.text",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596504695,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:160",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_unmap",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596504695,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602832114,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_unmap",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602832114,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603005416,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_unmap",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603005416,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604804044,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/platform/efi/early_printk.c:early_efi_unmap",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604804044,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604907433,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604907433,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 273
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604941291,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604941291,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609255127,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609255127,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612321436,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_cap_cpus",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612321436,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614461626,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614461626,
      "name": "early_iounmap",
      "section": ".init.text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615407051,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:163",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615407051,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 373
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617199170,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:164",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617199170,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627898672,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:164",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627898672,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 492
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619661712,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:162",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619661712,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621967760,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:162",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621967760,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510981584,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510981584,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243460880,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243460880,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604846751,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604846751,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604815807,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604815807,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604923935,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604923935,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void early_iounmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_iounmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604945462,
      "name": "early_iounmap",
      "external": true,
      "loc": "mm/early_ioremap.c:168",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:apple_airport_reset",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604945462,
      "name": "early_iounmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 261
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void early_iounmap(void * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void early_iounmap(void * addr, long unsigned int size)
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
