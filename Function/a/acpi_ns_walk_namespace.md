# Function: <code>acpi_ns_walk_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583692015,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:184",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583692015,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016379,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:184",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016379,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584158347,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:184",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158347,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225626,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:184",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225626,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584570585,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:184",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570585,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584795723,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584795723,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898114,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898114,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585101096,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585101096,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585237454,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237454,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585943253,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943253,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586066201,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586066201,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585943029,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943029,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586431322,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586431322,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587682412,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682412,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588992512,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992512,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 874
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589283024,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283024,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589744,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589744,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497563412,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497563412,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585095470,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095470,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585010824,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010824,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189038,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189038,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_ns_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585295198,
      "name": "acpi_ns_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nswalk.c:150",
      "file": "drivers/acpi/acpica/nswalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_get_devices",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585295198,
      "name": "acpi_ns_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
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
