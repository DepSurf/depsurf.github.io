# Function: <code>acpi_dm_compare_aml_resources</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584645723,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:599",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584871380,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584974909,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585178424,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585314777,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_dm_compare_aml_resources(u8 * aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 * aml2_buffer, acpi_rsdesc_size aml2_buffer_length)
```

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586020467,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586020467,
      "name": "acpi_dm_compare_aml_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void acpi_dm_compare_aml_resources(u8 * aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 * aml2_buffer, acpi_rsdesc_size aml2_buffer_length)
```

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586143240,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586143240,
      "name": "acpi_dm_compare_aml_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586020250,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586510643,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587766914,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void acpi_dm_compare_aml_resources(u8 * aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 * aml2_buffer, acpi_rsdesc_size aml2_buffer_length)
```

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589096704,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589096704,
      "name": "acpi_dm_compare_aml_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
void acpi_dm_compare_aml_resources(u8 * aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 * aml2_buffer, acpi_rsdesc_size aml2_buffer_length)
```

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589388544,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589388544,
      "name": "acpi_dm_compare_aml_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
void acpi_dm_compare_aml_resources(u8 * aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 * aml2_buffer, acpi_rsdesc_size aml2_buffer_length)
```

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589695744,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589695744,
      "name": "acpi_dm_compare_aml_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585266361,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_dm_compare_aml_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585372521,
      "name": "acpi_dm_compare_aml_resources",
      "external": false,
      "loc": "drivers/acpi/acpica/dbcmds.c:563",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void acpi_dm_compare_aml_resources(u8 * aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 * aml2_buffer, acpi_rsdesc_size aml2_buffer_length)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void acpi_dm_compare_aml_resources(u8 * aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 * aml2_buffer, acpi_rsdesc_size aml2_buffer_length)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void acpi_dm_compare_aml_resources(u8 * aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 * aml2_buffer, acpi_rsdesc_size aml2_buffer_length)
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
