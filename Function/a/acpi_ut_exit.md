# Function: <code>acpi_ut_exit</code>

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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619658,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:418",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619658,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845379,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845379,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584948756,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584948756,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151749,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151749,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288111,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288111,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994569,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994569,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586117415,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117415,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994124,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994124,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586483430,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483430,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737193,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737193,
      "name": "acpi_ut_exit",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589059776,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589059776,
      "name": "acpi_ut_exit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589351088,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351088,
      "name": "acpi_ut_exit",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589657936,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:403",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657936,
      "name": "acpi_ut_exit",
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585239695,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239695,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```

```json
{
  "name": "acpi_ut_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585345855,
      "name": "acpi_ut_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:398",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_all",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_clear_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_delete_result_if_not_used",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_push_walk_state",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object_descriptor",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_operands",
        "drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_enter_interpreter",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_simple_arg",
        "drivers/acpi/acpica/psscope.c:acpi_ps_cleanup_scope",
        "drivers/acpi/acpica/psscope.c:acpi_ps_pop_scope",
        "drivers/acpi/acpica/pstree.c:acpi_ps_append_arg",
        "drivers/acpi/acpica/pswalk.c:acpi_ps_delete_parse_tree",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_put_table",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585345855,
      "name": "acpi_ut_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
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
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_ut_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id)
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
