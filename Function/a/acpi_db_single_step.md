# Function: <code>acpi_db_single_step</code>

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
  "name": "acpi_db_single_step",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_single_step",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:83",
      "file": "drivers/acpi/acpica/dswexec.c",
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
  "name": "acpi_db_single_step",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_single_step",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:83",
      "file": "drivers/acpi/acpica/dswexec.c",
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
  "name": "acpi_db_single_step",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_single_step",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:83",
      "file": "drivers/acpi/acpica/dswexec.c",
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584667832,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:166",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667832,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584893952,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:130",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893952,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584997718,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997718,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201244,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201244,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585337605,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585337605,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044788,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044788,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586167818,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586167818,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586044461,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044461,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586536221,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586536221,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587793872,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587793872,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130752,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130752,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589422800,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589422800,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 777
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589730480,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589730480,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 777
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
  "name": "acpi_db_single_step",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_single_step",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:50",
      "file": "drivers/acpi/acpica/dswexec.c",
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
  "name": "acpi_db_single_step",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_single_step",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:50",
      "file": "drivers/acpi/acpica/dswexec.c",
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
  "name": "acpi_db_single_step",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_db_single_step",
      "external": false,
      "loc": "drivers/acpi/acpica/acdebug.h:50",
      "file": "drivers/acpi/acpica/dswexec.c",
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289189,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289189,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```

```json
{
  "name": "acpi_db_single_step",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585395349,
      "name": "acpi_db_single_step",
      "external": true,
      "loc": "drivers/acpi/acpica/dbxface.c:202",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395349,
      "name": "acpi_db_single_step",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
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
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state * walk_state, union acpi_parse_object * op, u32 opcode_class)
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
