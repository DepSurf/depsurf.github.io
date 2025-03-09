# Function: <code>acpi_tb_check_duplication</code>

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
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584603981,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:426",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584829740,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584933100,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585135957,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585272319,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977708,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977708,
      "name": "acpi_tb_check_duplication",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586100594,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586100594,
      "name": "acpi_tb_check_duplication",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977290,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977290,
      "name": "acpi_tb_check_duplication",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586465946,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586465946,
      "name": "acpi_tb_check_duplication",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718507,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:420",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718507,
      "name": "acpi_tb_check_duplication",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589035856,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:420",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589035856,
      "name": "acpi_tb_check_duplication",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589327008,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:420",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589327008,
      "name": "acpi_tb_check_duplication",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589633824,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:420",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589633824,
      "name": "acpi_tb_check_duplication",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585223903,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
  "name": "acpi_tb_check_duplication",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585330063,
      "name": "acpi_tb_check_duplication",
      "external": false,
      "loc": "drivers/acpi/acpica/tbdata.c:392",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
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
acpi_status acpi_tb_check_duplication(struct acpi_table_desc * table_desc, u32 * table_index)
```
</details>
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
