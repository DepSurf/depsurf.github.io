# Function: <code>acpi_put_table</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184970,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:365",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184970,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252620,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:365",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252620,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584612144,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:393",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584612144,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584837927,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837927,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584941284,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/dmar.c:dmar_platform_optin",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941284,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585144192,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_platform_optin",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144192,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585280553,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_platform_optin",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280553,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585986674,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_amd_sb_acs",
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/acpi_lpit.c:acpi_init_lpit",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/dmar.c:dmar_platform_optin",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986674,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586109554,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_amd_sb_acs",
        "drivers/acpi/tables.c:acpi_table_init_complete",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/acpi_lpit.c:acpi_init_lpit",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/iommu/amd/init.c:detect_ivrs",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/dmar.c:dmar_platform_optin",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109554,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585986343,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_amd_sb_acs",
        "drivers/acpi/tables.c:acpi_table_init_complete",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/acpi_lpit.c:acpi_init_lpit",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/dmar.c:dmar_platform_optin",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986343,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586475415,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_amd_sb_acs",
        "drivers/acpi/tables.c:acpi_table_init_complete",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/acpi_lpit.c:acpi_init_lpit",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/acpi/viot.c:acpi_viot_init",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/dmar.c:dmar_platform_optin",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586475415,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587728731,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_amd_sb_acs",
        "drivers/acpi/tables.c:acpi_table_init_complete",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/acpi_lpit.c:acpi_init_lpit",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/acpi/viot.c:acpi_viot_init",
        "drivers/acpi/viot.c:acpi_viot_early_init",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/dmar.c:dmar_platform_optin",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587728731,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589049008,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_amd_sb_acs",
        "drivers/acpi/tables.c:check_multiple_madt",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/acpi_lpit.c:acpi_init_lpit",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/acpi/viot.c:acpi_viot_init",
        "drivers/acpi/viot.c:acpi_viot_early_init",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589049008,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589340240,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_amd_sb_acs",
        "drivers/acpi/tables.c:check_multiple_madt",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/acpi_lpit.c:acpi_init_lpit",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/acpi/viot.c:acpi_viot_init",
        "drivers/acpi/viot.c:acpi_viot_early_init",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589340240,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589647056,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_amd_sb_acs",
        "drivers/acpi/tables.c:check_multiple_madt",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/acpi_fpdt.c:acpi_init_fpdt",
        "drivers/acpi/acpi_lpit.c:acpi_init_lpit",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_get_wdat",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/apei/hest.c:acpi_hest_init",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/acpi/viot.c:acpi_viot_init",
        "drivers/acpi/viot.c:acpi_viot_early_init",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_tis.c:check_acpi_tpm2",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/iommu/intel/dmar.c:detect_intel_iommu",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647056,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497596056,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/acpi.c:acpi_boot_table_init",
        "drivers/irqchip/irq-gic-v2m.c:acpi_parse_madt_msi",
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/acpi/pptt.c:find_acpi_cpu_cache_topology",
        "drivers/acpi/pptt.c:acpi_pptt_cpu_is_thread",
        "drivers/acpi/pptt.c:cache_setup_acpi",
        "drivers/acpi/pptt.c:acpi_find_last_cache_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497596056,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585124609,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_platform_optin",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124609,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585039911,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/nfit/core.c:acpi_nfit_add",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_platform_optin",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585039911,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585232137,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_platform_optin",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232137,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_put_table(struct acpi_table_header * table)
```

```json
{
  "name": "acpi_put_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585338297,
      "name": "acpi_put_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:359",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/sysfs.c:acpi_table_show",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/hmat/hmat.c:hmat_init",
        "drivers/acpi/spcr.c:acpi_parse_spcr",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_platform_optin",
        "drivers/iommu/dmar.c:detect_intel_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585338297,
      "name": "acpi_put_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void acpi_put_table(struct acpi_table_header * table)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_put_table(struct acpi_table_header * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_put_table(struct acpi_table_header * table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_put_table(struct acpi_table_header * table)
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
