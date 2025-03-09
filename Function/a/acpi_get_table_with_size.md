# Function: <code>acpi_get_table_with_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_table_with_size(char * signature, u32 instance, struct acpi_table_header * * out_table, acpi_size * tbl_size)
```

```json
{
  "name": "acpi_get_table_with_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583718248,
      "name": "acpi_get_table_with_size",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:282",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/dmar.c:dmar_table_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718248,
      "name": "acpi_get_table_with_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
acpi_status acpi_get_table_with_size(char * signature, u32 instance, struct acpi_table_header * * out_table, acpi_size * tbl_size)
```

```json
{
  "name": "acpi_get_table_with_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584042563,
      "name": "acpi_get_table_with_size",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:282",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/tables.c:acpi_table_init",
        "drivers/acpi/tables.c:acpi_table_parse",
        "drivers/acpi/tables.c:acpi_table_parse_entries_array",
        "drivers/acpi/processor_core.c:acpi_map_madt_entry",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_table_detect",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042563,
      "name": "acpi_get_table_with_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
acpi_status acpi_get_table_with_size(char * signature, u32 instance, struct acpi_table_header * * out_table, acpi_size * tbl_size)
```
</details>
</li>
</ul>
