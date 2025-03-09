# Function: <code>acpi_ut_get_type_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583723785,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:223",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723785,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584048344,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:224",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584048268,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584190619,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:225",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584190543,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584258225,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:225",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258149,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584621587,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:225",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_method",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621136,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584847304,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_method",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846853,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584950681,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950230,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585153690,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153236,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585290052,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289598,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585996068,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:192",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585996068,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118914,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:192",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118914,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995623,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:192",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995623,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586484969,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:192",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484969,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739174,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:192",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739174,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589062599,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:192",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589062432,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589353911,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:192",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353744,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589660759,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:192",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660592,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497606668,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497606548,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585129768,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585129692,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585045023,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585044947,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585241636,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241182,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```

```json
{
  "name": "acpi_ut_get_type_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585347796,
      "name": "acpi_ut_get_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:191",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdecode.c:acpi_ut_get_object_type_name"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_clear",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_package_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_acpi_compliance",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585347342,
      "name": "acpi_ut_get_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>const char *</code>
</li>
</ul>
</details>
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
const char * acpi_ut_get_type_name(acpi_object_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const char * acpi_ut_get_type_name(acpi_object_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const char * acpi_ut_get_type_name(acpi_object_type type)
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
