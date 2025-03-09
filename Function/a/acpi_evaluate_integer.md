# Function: <code>acpi_evaluate_integer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583541803,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:286",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status_handle",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:dock_present",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/button.c:acpi_lid_send_state",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541803,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583862748,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:283",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status_handle",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/dock.c:dock_present",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583862748,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001824,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:283",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status_handle",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_core.c:set_processor_node_mapping",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/dock.c:dock_present",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001824,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050960,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:283",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050960,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317984,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:283",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317984,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584538272,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:283",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538272,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584635488,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:283",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635488,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835328,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:270",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/soundwire/slave.c:sdw_acpi_find_slaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835328,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584971056,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:270",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971056,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585666640,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:270",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:processor_physically_present",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/ac.c:get_ac_property",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/numa/srat.c:acpi_get_node",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666640,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585792016,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:266",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:processor_physically_present",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/ac.c:acpi_ac_add",
        "drivers/acpi/ac.c:get_ac_property",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/numa/srat.c:acpi_get_node",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585792016,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585674672,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:247",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:hrv_show",
        "drivers/acpi/device_sysfs.c:sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:uid_show",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/numa/srat.c:acpi_get_node",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585674672,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586154064,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:247",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_get_local_address",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:hrv_show",
        "drivers/acpi/device_sysfs.c:sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:uid_show",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:__get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/numa/srat.c:acpi_get_node",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586154064,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587387712,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:247",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_dev_match_cb",
        "drivers/acpi/utils.c:acpi_get_local_address",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:hrv_show",
        "drivers/acpi/device_sysfs.c:sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:uid_show",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:__get_state",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/numa/srat.c:acpi_get_node",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587387712,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588638704,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:247",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_dev_match_cb",
        "drivers/acpi/utils.c:acpi_get_local_address",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:hrv_show",
        "drivers/acpi/device_sysfs.c:sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_power_state_for_wake",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:uid_show",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:__get_state",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/numa/srat.c:acpi_get_node",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588638704,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588926368,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:247",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_dev_match_cb",
        "drivers/acpi/utils.c:acpi_get_local_address",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:hrv_show",
        "drivers/acpi/device_sysfs.c:sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_power_state_for_wake",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:uid_show",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:__get_state",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_get_info",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/numa/srat.c:acpi_get_node",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support",
        "drivers/thermal/thermal_acpi.c:thermal_acpi_trip_temp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588926368,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589222736,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:247",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_dev_match_cb",
        "drivers/acpi/utils.c:acpi_get_local_address",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:hrv_show",
        "drivers/acpi/device_sysfs.c:sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_power_state_for_wake",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:processor_physically_present",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:uid_show",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:__get_state",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/pci_slot.c:check_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal_lib.c:acpi_trip_temp",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_get_trip_points",
        "drivers/acpi/thermal.c:acpi_thermal_get_trip_points",
        "drivers/acpi/thermal.c:acpi_thermal_get_trip_points",
        "drivers/acpi/thermal.c:acpi_thermal_get_trip_points",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/numa/srat.c:acpi_get_node",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/gpu/drm/drm_privacy_screen_x86.c:detect_thinkpad_privacy_screen",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222736,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497384712,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:270",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/pci-acpi.c:acpi_match_rc",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/bus.c:acpi_bus_get_status",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497384712,
      "name": "acpi_evaluate_integer",
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584918496,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:270",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918496,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584824368,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:270",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584824368,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584922640,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:270",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584922640,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```

```json
{
  "name": "acpi_evaluate_integer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585028784,
      "name": "acpi_evaluate_integer",
      "external": true,
      "loc": "drivers/acpi/utils.c:270",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:status_show",
        "drivers/acpi/device_sysfs.c:acpi_device_hrv_show",
        "drivers/acpi/device_sysfs.c:acpi_device_sun_show",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_get_power",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/dock.c:show_dock_uid",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/acpi/power.c:acpi_power_get_state",
        "drivers/acpi/numa.c:acpi_get_node",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/button.c:acpi_lid_input_open",
        "drivers/acpi/button.c:acpi_button_resume",
        "drivers/acpi/button.c:acpi_lid_update_state",
        "drivers/acpi/button.c:acpi_lid_open",
        "drivers/acpi/button.c:acpi_button_state_seq_show",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/pci_slot.c:register_slot",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_get_temperature",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585028784,
      "name": "acpi_evaluate_integer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list * arguments, long long unsigned int * data)
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
