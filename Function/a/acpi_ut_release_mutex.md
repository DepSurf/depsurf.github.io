# Function: <code>acpi_ut_release_mutex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730809,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:324",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_start_trace_method",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsload.c:acpi_ns_load_table",
        "drivers/acpi/acpica/nsload.c:acpi_ns_load_table",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730809,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055108,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:308",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsload.c:acpi_ns_load_table",
        "drivers/acpi/acpica/nsload.c:acpi_ns_load_table",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055108,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197472,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:308",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_put_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197472,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584265092,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:308",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_put_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584265092,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584632973,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:308",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632973,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858634,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858634,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584962128,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962128,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585165283,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585165283,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585301630,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301630,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586008088,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_install_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_install_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008088,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586130917,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_install_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_install_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130917,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586007702,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_install_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007702,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586497646,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_install_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586497646,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587752671,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfobj.c:acpi_get_type",
        "drivers/acpi/acpica/nsxfobj.c:acpi_get_type",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_install_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587752671,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589079120,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfregn.c:acpi_execute_reg_methods",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_internal",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_data",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfobj.c:acpi_get_type",
        "drivers/acpi/acpica/nsxfobj.c:acpi_get_type",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_install_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589079120,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589370784,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfregn.c:acpi_execute_reg_methods",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_internal",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_data",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfobj.c:acpi_get_type",
        "drivers/acpi/acpica/nsxfobj.c:acpi_get_type",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_install_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589370784,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589677888,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_global_event_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/evxfregn.c:acpi_execute_reg_methods",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/evxfregn.c:acpi_install_address_space_handler_internal",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_data",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfobj.c:acpi_get_type",
        "drivers/acpi/acpica/nsxfobj.c:acpi_get_type",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_delete_namespace_by_owner",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_install_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589677888,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497615156,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497615156,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585136934,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585136934,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585052174,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585052174,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585253214,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585253214,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```

```json
{
  "name": "acpi_ut_release_mutex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585359374,
      "name": "acpi_ut_release_mutex",
      "external": true,
      "loc": "drivers/acpi/acpica/utmutex.c:273",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_region_handlers",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_initialize_op_regions",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/exutils.c:acpi_ex_exit_interpreter",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/psxface.c:acpi_debug_trace",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_set_table_loaded_flag",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_is_table_loaded",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_get_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_release_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_allocate_owner_id",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_terminate",
        "drivers/acpi/acpica/tbfind.c:acpi_tb_find_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbxface.c:acpi_remove_table_handler",
        "drivers/acpi/acpica/tbxface.c:acpi_reallocate_root_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_release_owner_id",
        "drivers/acpi/acpica/utownerid.c:acpi_ut_allocate_owner_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585359374,
      "name": "acpi_ut_release_mutex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ut_release_mutex(acpi_mutex_handle mutex_id)
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
