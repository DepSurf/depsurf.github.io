# Function: <code>acpi_ps_get_opcode_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583701796,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:69",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701796,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584026173,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:69",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026173,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584168082,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:69",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584168082,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235507,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:69",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235507,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584585398,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:69",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585398,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584810932,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584810932,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913496,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913496,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116142,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116142,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585252501,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585252501,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585958430,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585958430,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586081348,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081348,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585958149,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585958149,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586446448,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586446448,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587697961,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697961,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589011369,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011088,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589301909,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589301664,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589608677,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589608432,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497574484,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497574484,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585105993,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585105993,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585021320,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585021320,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204085,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204085,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```

```json
{
  "name": "acpi_ps_get_opcode_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585310245,
      "name": "acpi_ps_get_opcode_info",
      "external": true,
      "loc": "drivers/acpi/acpica/psopinfo.c:35",
      "file": "drivers/acpi/acpica/psopinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psopinfo.c:acpi_ps_get_opcode_name",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585310245,
      "name": "acpi_ps_get_opcode_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const struct acpi_opcode_info * acpi_ps_get_opcode_info(u16 opcode)
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
