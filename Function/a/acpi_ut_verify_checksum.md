# Function: <code>acpi_ut_verify_checksum</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_verify_checksum(struct acpi_table_header * table, u32 length)
```

```json
{
  "name": "acpi_ut_verify_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589054928,
      "name": "acpi_ut_verify_checksum",
      "external": true,
      "loc": "drivers/acpi/acpica/utcksum.c:35",
      "file": "drivers/acpi/acpica/utcksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589054928,
      "name": "acpi_ut_verify_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
acpi_status acpi_ut_verify_checksum(struct acpi_table_header * table, u32 length)
```

```json
{
  "name": "acpi_ut_verify_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589346160,
      "name": "acpi_ut_verify_checksum",
      "external": true,
      "loc": "drivers/acpi/acpica/utcksum.c:35",
      "file": "drivers/acpi/acpica/utcksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589346160,
      "name": "acpi_ut_verify_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
acpi_status acpi_ut_verify_checksum(struct acpi_table_header * table, u32 length)
```

```json
{
  "name": "acpi_ut_verify_checksum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589653008,
      "name": "acpi_ut_verify_checksum",
      "external": true,
      "loc": "drivers/acpi/acpica/utcksum.c:35",
      "file": "drivers/acpi/acpica/utcksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653008,
      "name": "acpi_ut_verify_checksum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
acpi_status acpi_ut_verify_checksum(struct acpi_table_header * table, u32 length)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
