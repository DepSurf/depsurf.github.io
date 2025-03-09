# Function: <code>acpi_ut_create_internal_object_dbg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732325,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:86",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732325,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056571,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:86",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056571,
      "name": "acpi_ut_create_internal_object_dbg",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584198409,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:86",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198409,
      "name": "acpi_ut_create_internal_object_dbg",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584266020,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:86",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266020,
      "name": "acpi_ut_create_internal_object_dbg",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584634967,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:86",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634967,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584860685,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584860685,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964179,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964179,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167355,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167355,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585303702,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303702,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586010431,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_create_method_mutex",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586010431,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586133243,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_create_method_mutex",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586133243,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586009786,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009786,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586499809,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586499809,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587755026,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755026,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589081904,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589081904,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589373648,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589373648,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589680752,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680752,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497616532,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497616532,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585137930,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585137930,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585053135,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_add_table",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053135,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585255286,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585255286,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```

```json
{
  "name": "acpi_ut_create_internal_object_dbg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585361446,
      "name": "acpi_ut_create_internal_object_dbg",
      "external": true,
      "loc": "drivers/acpi/acpica/utobject.c:53",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585361446,
      "name": "acpi_ut_create_internal_object_dbg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
union acpi_operand_object * acpi_ut_create_internal_object_dbg(const char * module_name, u32 line_number, u32 component_id, acpi_object_type type)
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
