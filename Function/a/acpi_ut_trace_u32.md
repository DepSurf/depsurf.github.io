# Function: <code>acpi_ut_trace_u32</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620703,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:383",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620703,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846420,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846420,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949797,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949797,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585152795,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585152795,
      "name": "acpi_ut_trace_u32",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289157,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289157,
      "name": "acpi_ut_trace_u32",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995624,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995624,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118470,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118470,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995179,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995179,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586484485,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484485,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738526,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738526,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589061600,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589061600,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589352912,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589352912,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589659760,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:368",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589659760,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585240741,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240741,
      "name": "acpi_ut_trace_u32",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```

```json
{
  "name": "acpi_ut_trace_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346901,
      "name": "acpi_ut_trace_u32",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:363",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_write_with_update_rule",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/hwxface.c:acpi_read_bit_register",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346901,
      "name": "acpi_ut_trace_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
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
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_ut_trace_u32(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u32 integer)
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
