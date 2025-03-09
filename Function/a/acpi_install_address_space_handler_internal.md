# Function: <code>acpi_install_address_space_handler_internal</code>

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
acpi_status acpi_install_address_space_handler_internal(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context, u8 run_reg)
```

```json
{
  "name": "acpi_install_address_space_handler_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588871840,
      "name": "acpi_install_address_space_handler_internal",
      "external": false,
      "loc": "drivers/acpi/acpica/evxfregn.c:46",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_no_reg",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588871840,
      "name": "acpi_install_address_space_handler_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
acpi_status acpi_install_address_space_handler_internal(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context, u8 run_reg)
```

```json
{
  "name": "acpi_install_address_space_handler_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589161280,
      "name": "acpi_install_address_space_handler_internal",
      "external": false,
      "loc": "drivers/acpi/acpica/evxfregn.c:46",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_no_reg",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589161280,
      "name": "acpi_install_address_space_handler_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
acpi_status acpi_install_address_space_handler_internal(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context, u8 run_reg)
```

```json
{
  "name": "acpi_install_address_space_handler_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589467648,
      "name": "acpi_install_address_space_handler_internal",
      "external": false,
      "loc": "drivers/acpi/acpica/evxfregn.c:46",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_no_reg",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589467648,
      "name": "acpi_install_address_space_handler_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
acpi_status acpi_install_address_space_handler_internal(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context, u8 run_reg)
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
