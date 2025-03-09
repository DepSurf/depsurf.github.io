# Function: <code>acpi_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737960,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:104",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737960,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062142,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:104",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062142,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204353,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:104",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_pstate_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204353,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584271948,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:104",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_pstate_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584271948,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644007,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:104",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644007,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869673,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869673,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584973200,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973200,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176500,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176500,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585312853,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312853,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586019390,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/ac.c:get_ac_property",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_pstate_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586019390,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586142180,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/ac.c:get_ac_property",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_pstate_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142180,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586018945,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018945,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586509293,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586509293,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587765339,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765339,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589095248,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589095248,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589387088,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387088,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589694288,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_terminate",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589694288,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497625000,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_perflib.c:acpi_processor_pstate_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497625000,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585144654,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_pstate_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144654,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585059844,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_pstate_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059844,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585264437,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585264437,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```

```json
{
  "name": "acpi_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585370597,
      "name": "acpi_exception",
      "external": true,
      "loc": "drivers/acpi/acpica/utxferror.c:68",
      "file": "drivers/acpi/acpica/utxferror.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operands",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_get_predicate_value",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_install_xrupt_handlers",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeinit.c:acpi_ev_gpe_initialize",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_detach_region",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock",
        "drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_set_mode",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop",
        "drivers/acpi/acpica/psobject.c:acpi_ps_build_named_op",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_resources_to_aml",
        "drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_tb_load_namespace",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/tbxfload.c:acpi_load_tables",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/utxfinit.c:acpi_initialize_subsystem",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbinput.c:acpi_db_user_commands",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585370597,
      "name": "acpi_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_exception(const char * module_name, u32 line_number, acpi_status status, const char * format, void (anon))
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
