# Function: <code>acpi_db_match_command_help</code>

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
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584657191,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:353",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584883235,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:333",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584986793,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:333",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585190310,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:333",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585326663,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:333",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
u8 acpi_db_match_command_help(const char * command, const struct acpi_db_command_help * help)
```

```json
{
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586033479,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:337",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586033479,
      "name": "acpi_db_match_command_help",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
u8 acpi_db_match_command_help(const char * command, const struct acpi_db_command_help * help)
```

```json
{
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586156300,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:340",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586156300,
      "name": "acpi_db_match_command_help",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586033049,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:340",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586524052,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:340",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587781017,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:340",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589114143,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:340",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589406095,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:340",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589713695,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:343",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585278247,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:333",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
  "name": "acpi_db_match_command_help",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585384407,
      "name": "acpi_db_match_command_help",
      "external": false,
      "loc": "drivers/acpi/acpica/dbinput.c:333",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
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
u8 acpi_db_match_command_help(const char * command, const struct acpi_db_command_help * help)
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
u8 acpi_db_match_command_help(const char * command, const struct acpi_db_command_help * help)
```
</details>
</li>
</ul>
