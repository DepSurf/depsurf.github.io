# Function: <code>acpi_tb_invalidate_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712482,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:306",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712482,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584036902,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:306",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036902,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584179060,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:307",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584179060,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584246748,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:307",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246748,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584603495,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:359",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584603495,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584829254,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584829254,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584932610,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932610,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585135468,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585135468,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585271830,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271830,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585978221,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978221,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586101107,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101107,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585977939,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977939,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586466595,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466595,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719233,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:341",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719233,
      "name": "acpi_tb_invalidate_table",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037088,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:341",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037088,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589328256,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:341",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328256,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589635072,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:341",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635072,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497588576,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497588576,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118079,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118079,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585033391,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585033391,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585223414,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585223414,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```

```json
{
  "name": "acpi_tb_invalidate_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585329574,
      "name": "acpi_tb_invalidate_table",
      "external": true,
      "loc": "drivers/acpi/acpica/tbdata.c:325",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329574,
      "name": "acpi_tb_invalidate_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc * table_desc)
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
