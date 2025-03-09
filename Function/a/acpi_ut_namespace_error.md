# Function: <code>acpi_ut_namespace_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_namespace_error(const char * module_name, u32 line_number, const char * internal_name, acpi_status lookup_status)
```

```json
{
  "name": "acpi_ut_namespace_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725916,
      "name": "acpi_ut_namespace_error",
      "external": true,
      "loc": "drivers/acpi/acpica/uterror.c:199",
      "file": "drivers/acpi/acpica/uterror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725916,
      "name": "acpi_ut_namespace_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void acpi_ut_namespace_error(const char * module_name, u32 line_number, const char * internal_name, acpi_status lookup_status)
```

```json
{
  "name": "acpi_ut_namespace_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050396,
      "name": "acpi_ut_namespace_error",
      "external": true,
      "loc": "drivers/acpi/acpica/uterror.c:199",
      "file": "drivers/acpi/acpica/uterror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050396,
      "name": "acpi_ut_namespace_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void acpi_ut_namespace_error(const char * module_name, u32 line_number, const char * internal_name, acpi_status lookup_status)
```

```json
{
  "name": "acpi_ut_namespace_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192671,
      "name": "acpi_ut_namespace_error",
      "external": true,
      "loc": "drivers/acpi/acpica/uterror.c:199",
      "file": "drivers/acpi/acpica/uterror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192671,
      "name": "acpi_ut_namespace_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void acpi_ut_namespace_error(const char * module_name, u32 line_number, const char * internal_name, acpi_status lookup_status)
```

```json
{
  "name": "acpi_ut_namespace_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260303,
      "name": "acpi_ut_namespace_error",
      "external": true,
      "loc": "drivers/acpi/acpica/uterror.c:199",
      "file": "drivers/acpi/acpica/uterror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260303,
      "name": "acpi_ut_namespace_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void acpi_ut_namespace_error(const char * module_name, u32 line_number, const char * internal_name, acpi_status lookup_status)
```

```json
{
  "name": "acpi_ut_namespace_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625023,
      "name": "acpi_ut_namespace_error",
      "external": true,
      "loc": "drivers/acpi/acpica/uterror.c:199",
      "file": "drivers/acpi/acpica/uterror.c",
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
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625023,
      "name": "acpi_ut_namespace_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void acpi_ut_namespace_error(const char * module_name, u32 line_number, const char * internal_name, acpi_status lookup_status)
```
</details>
</li>
</ul>
