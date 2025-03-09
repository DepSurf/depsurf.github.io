# Function: <code>acpi_ut_ptr_exit</code>

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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620819,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:544",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620819,
      "name": "acpi_ut_ptr_exit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846536,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846536,
      "name": "acpi_ut_ptr_exit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949913,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949913,
      "name": "acpi_ut_ptr_exit",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585152909,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585152909,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289271,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289271,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995739,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995739,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118585,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118585,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995294,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995294,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586484600,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484600,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738661,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738661,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589061808,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589061808,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353120,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353120,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589659968,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:529",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589659968,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585240855,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240855,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```

```json
{
  "name": "acpi_ut_ptr_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585347015,
      "name": "acpi_ut_ptr_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:524",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_pop_walk_state",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namestring",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_end",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/tbxfroot.c:acpi_tb_scan_memory_for_rsdp",
        "drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585347015,
      "name": "acpi_ut_ptr_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
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
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_ut_ptr_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u8 * ptr)
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
