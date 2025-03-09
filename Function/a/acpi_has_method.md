# Function: <code>acpi_has_method</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583543283,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:553",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_dock_match",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543283,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583864217,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:550",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_dock_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864217,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584003293,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:550",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_dock_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003293,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584052576,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:550",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052576,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319488,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:551",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319488,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584539792,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:551",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539792,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584637008,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:551",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637008,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584836832,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:538",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584836832,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972560,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:538",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972560,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667744,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:545",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_scan_init_hotplug",
        "drivers/acpi/scan.c:acpi_scan_init_hotplug",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_ibm_smbus_match",
        "drivers/acpi/scan.c:acpi_ibm_smbus_match",
        "drivers/acpi/scan.c:acpi_ibm_smbus_match",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_init_power_state",
        "drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_has_acpi_ppc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667744,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585793520,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:541",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_init_hotplug",
        "drivers/acpi/scan.c:acpi_scan_init_hotplug",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_ibm_smbus_match",
        "drivers/acpi/scan.c:acpi_ibm_smbus_match",
        "drivers/acpi/scan.c:acpi_ibm_smbus_match",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_init_power_state",
        "drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_has_acpi_ppc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793520,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673296,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:535",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673296,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152864,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:549",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152864,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587386080,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:549",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pr3_present",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_bay_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_dep",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/reset/core.c:__device_reset",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587386080,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588636160,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:587",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pr3_present",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_bay_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_dep",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/reset/core.c:__device_reset",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636160,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588923904,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:587",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pr3_present",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_bay_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_dep",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/reset/core.c:__device_reset",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588923904,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589223922,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:659",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_device_dep"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_pr3_present",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpi_pcihp.c:check_hotplug",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_bay_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/reset/core.c:__device_reset",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219072,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497386616,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:538",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/qcom-irq-combiner.c:combiner_probe",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_probe",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497386616,
      "name": "acpi_has_method",
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584920128,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:538",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920128,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584826000,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:538",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826000,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924144,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:538",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924144,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```

```json
{
  "name": "acpi_has_method",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585030288,
      "name": "acpi_has_method",
      "external": true,
      "loc": "drivers/acpi/utils.c:538",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_remove_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_device_dep_initialize",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/scan.c:acpi_ata_match",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585030288,
      "name": "acpi_has_method",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool acpi_has_method(acpi_handle handle, char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool acpi_has_method(acpi_handle handle, char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool acpi_has_method(acpi_handle handle, char * name)
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
