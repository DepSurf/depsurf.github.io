# Function: <code>acpi_warning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737317,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:144",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737317,
      "name": "acpi_warning",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061491,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:145",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061491,
      "name": "acpi_warning",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203702,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:145",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203702,
      "name": "acpi_warning",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584271297,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:145",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584271297,
      "name": "acpi_warning",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643356,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:145",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643356,
      "name": "acpi_warning",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869040,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869040,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972567,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972567,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585175859,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175859,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585312212,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312212,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586018749,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018749,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586141539,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141539,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586018304,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018304,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586508652,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508652,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587764558,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587764558,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589094368,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589094368,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589386208,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386208,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589693408,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxfevnt.c:acpi_enable",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589693408,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497624244,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497624244,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585144013,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144013,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585059203,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059203,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585263796,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263796,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585369956,
      "name": "acpi_warning",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:109",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_get_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstring.c:acpi_ut_repair_name",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369956,
      "name": "acpi_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_warning(const char * module_name, u32 line_number, const char * format, void (anon))
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
