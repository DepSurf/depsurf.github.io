# Function: <code>acpi_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_info(const char * module_name, u32 line_number, const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737484,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:178",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737484,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061658,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:178",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061658,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203869,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:178",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203869,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584271464,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:174",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584271464,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643523,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:174",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643523,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869202,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869202,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972729,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972729,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176023,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176023,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585312376,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312376,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586018913,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018913,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586141703,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141703,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586018468,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018468,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586508816,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508816,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587764757,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587764757,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589094592,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589094592,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589386432,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386432,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589693632,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589693632,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497624440,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497624440,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585144177,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144177,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585059367,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059367,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585263960,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263960,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void acpi_info(const char * format, void (anon))
```

```json
{
  "name": "acpi_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585370120,
      "name": "acpi_info",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:138",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table",
        "drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbprint.c:acpi_tb_print_table_header",
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_table_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585370120,
      "name": "acpi_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
<b>Param removed. </b>
<code>const char * module_name</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 line_number</code>
</li>
<li>
<b>Param reordered. </b>
<code>module_name, line_number, format, (anon)</code> ➡️ <code>format, (anon)</code>
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
void acpi_info(const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_info(const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_info(const char * format, void (anon))
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
