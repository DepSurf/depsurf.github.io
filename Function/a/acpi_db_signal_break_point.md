# Function: <code>acpi_db_signal_break_point</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_signal_break_point",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:88",
      "file": "drivers/acpi/acpica/dscontrol.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_signal_break_point",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:88",
      "file": "drivers/acpi/acpica/dscontrol.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_signal_break_point",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:88",
      "file": "drivers/acpi/acpica/dscontrol.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584667784,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:133",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667784,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584893904,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:97",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893904,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584997670,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997670,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201195,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201195,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585337556,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585337556,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044739,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044739,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167769,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167769,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044412,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044412,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586536172,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586536172,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587793807,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587793807,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130656,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130656,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589422704,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589422704,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589730384,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589730384,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_signal_break_point",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:55",
      "file": "drivers/acpi/acpica/dscontrol.c",
      "inline": "declared, inlined",
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
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_signal_break_point",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:55",
      "file": "drivers/acpi/acpica/dscontrol.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_signal_break_point",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:55",
      "file": "drivers/acpi/acpica/dscontrol.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289140,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289140,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_db_signal_break_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585395300,
      "name": "acpi_db_signal_break_point",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:105",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dscontrol.c:acpi_ds_exec_end_control_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395300,
      "name": "acpi_db_signal_break_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_db_signal_break_point(struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
