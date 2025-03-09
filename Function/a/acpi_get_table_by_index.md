# Function: <code>acpi_get_table_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583718493,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:355",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718493,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584042807,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:355",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042807,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584185372,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:407",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185372,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252515,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:407",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252515,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584611934,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:439",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584611934,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584837717,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837717,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584941074,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941074,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585143982,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143982,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585280343,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280343,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585986135,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986135,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586109015,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109015,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585985811,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585985811,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586474883,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586474883,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587728366,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587728366,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589048192,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048192,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589339424,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589339424,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646240,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_tables_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646240,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497595260,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497595260,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585123993,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123993,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585039295,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585039295,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585231927,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585231927,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```

```json
{
  "name": "acpi_get_table_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585338087,
      "name": "acpi_get_table_by_index",
      "external": true,
      "loc": "drivers/acpi/acpica/tbxface.c:405",
      "file": "drivers/acpi/acpica/tbxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_load_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585338087,
      "name": "acpi_get_table_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_table_header * * out_table</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_table_header * * table</code>
</li>
</ul>
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header * * out_table)
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
