# Function: <code>acpi_ut_trace_ptr</code>

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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620471,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:310",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620471,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846188,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846188,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949565,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949565,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585152567,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585152567,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288929,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288929,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995394,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_get_arguments",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_package_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995394,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118240,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_get_arguments",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_get_aml_opcode",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_package_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118240,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994949,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994949,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586484255,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484255,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738256,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738256,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589061184,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589061184,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589352496,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589352496,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589659344,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:295",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589659344,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585240513,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240513,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```

```json
{
  "name": "acpi_ut_trace_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346673,
      "name": "acpi_ut_trace_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:290",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_package_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments",
        "drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_index_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_bank_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_init_field_objects",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_evaluate_name_path",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_resolve_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_begin_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_string",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_buffer",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex_object",
        "drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio",
        "drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string",
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_secondary_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_final_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_create_op",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/psparse.c:acpi_ps_next_parse_state",
        "drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_push_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_init_scope",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346673,
      "name": "acpi_ut_trace_ptr",
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
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
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_ut_trace_ptr(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const void * pointer)
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
