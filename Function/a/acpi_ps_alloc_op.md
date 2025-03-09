# Function: <code>acpi_ps_alloc_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704055,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:116",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704055,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028452,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:116",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028452,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584170373,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:116",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170373,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237857,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:117",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237857,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584589206,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:117",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589206,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814730,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814730,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584917450,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917450,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585120121,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585120121,
      "name": "acpi_ps_alloc_op",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585256483,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585256483,
      "name": "acpi_ps_alloc_op",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962412,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962412,
      "name": "acpi_ps_alloc_op",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586085330,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085330,
      "name": "acpi_ps_alloc_op",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962133,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962133,
      "name": "acpi_ps_alloc_op",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586450487,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586450487,
      "name": "acpi_ps_alloc_op",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587702244,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587702244,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589016512,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589016512,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589307072,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589307072,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589613840,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589613840,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497577320,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497577320,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585108423,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108423,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585023745,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585023745,
      "name": "acpi_ps_alloc_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585208067,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585208067,
      "name": "acpi_ps_alloc_op",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```

```json
{
  "name": "acpi_ps_alloc_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314227,
      "name": "acpi_ps_alloc_op",
      "external": true,
      "loc": "drivers/acpi/acpica/psutils.c:85",
      "file": "drivers/acpi/acpica/psutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314227,
      "name": "acpi_ps_alloc_op",
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
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
union acpi_parse_object * acpi_ps_alloc_op(u16 opcode, u8 * aml)
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
