# Function: <code>acpi_debug_print_raw</code>

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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619870,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:236",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619870,
      "name": "acpi_debug_print_raw",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845591,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845591,
      "name": "acpi_debug_print_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584948968,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584948968,
      "name": "acpi_debug_print_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151974,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151974,
      "name": "acpi_debug_print_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288336,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288336,
      "name": "acpi_debug_print_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994796,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994796,
      "name": "acpi_debug_print_raw",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586117642,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117642,
      "name": "acpi_debug_print_raw",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994351,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994351,
      "name": "acpi_debug_print_raw",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586483657,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483657,
      "name": "acpi_debug_print_raw",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737530,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737530,
      "name": "acpi_debug_print_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589060176,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589060176,
      "name": "acpi_debug_print_raw",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589351488,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351488,
      "name": "acpi_debug_print_raw",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589658336,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:221",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589658336,
      "name": "acpi_debug_print_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585239920,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239920,
      "name": "acpi_debug_print_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```

```json
{
  "name": "acpi_debug_print_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346080,
      "name": "acpi_debug_print_raw",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:216",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_parse_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table",
        "drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346080,
      "name": "acpi_debug_print_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
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
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_debug_print_raw(u32 requested_debug_level, u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * format, void (anon))
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
