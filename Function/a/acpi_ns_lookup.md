# Function: <code>acpi_ns_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583677363,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:280",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677363,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001069,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001069,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584142517,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584142517,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584209800,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:285",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209800,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584541690,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:285",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541690,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2057
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584766170,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:249",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584766170,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2052
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584867790,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:249",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867790,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2133
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072488,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072488,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2150
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585208822,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585208822,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2150
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585914663,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585914663,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2146
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586036373,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:280",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036373,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2146
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585913200,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:280",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913200,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2143
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401279,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:280",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401279,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2143
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587650645,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:280",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587650645,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2121
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588953936,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:280",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588953936,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2609
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589243904,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:280",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243904,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2647
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589550528,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:280",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589550528,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2647
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497544512,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497544512,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1064
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585079782,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585079782,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584995193,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584995193,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585160406,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585160406,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2150
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585266566,
      "name": "acpi_ns_lookup",
      "external": true,
      "loc": "drivers/acpi/acpica/nsaccess.c:281",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266566,
      "name": "acpi_ns_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2150
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
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ns_lookup(union acpi_generic_state * scope_info, char * pathname, acpi_object_type type, acpi_interpreter_mode interpreter_mode, u32 flags, struct acpi_walk_state * walk_state, struct acpi_namespace_node * * return_node)
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
