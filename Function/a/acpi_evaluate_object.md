# Function: <code>acpi_evaluate_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583692465,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:175",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_core.c:acpi_get_phys_id",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583692465,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016839,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:175",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016839,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584158807,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:175",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_core.c:set_processor_node_mapping",
        "drivers/acpi/processor_core.c:__acpi_get_phys_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158807,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226239,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:198",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_turn_off_unused_power_resources",
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226239,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584571572,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:198",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571572,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 927
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584796713,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_initial_sync",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584796713,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584899104,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584899104,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585102096,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585102096,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585238454,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238454,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585943959,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:acpi_run_hpp",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_run_oshp",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_reg",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_init_power_state",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_core.c:map_mat_entry",
        "drivers/acpi/processor_pdc.c:processor_physically_present",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/acpi/fan.c:acpi_fan_get_fif",
        "drivers/acpi/fan.c:fan_get_state_acpi4",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_push_id",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943959,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586066890,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:acpi_run_hpp",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_run_oshp",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_reg",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_init_power_state",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_core.c:map_mat_entry",
        "drivers/acpi/processor_pdc.c:processor_physically_present",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/acpi/fan.c:acpi_fan_get_fif",
        "drivers/acpi/fan.c:fan_get_state_acpi4",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_push_id",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586066890,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585943711,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_reg",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943711,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586432004,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_reg",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_off",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_get_fps",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586432004,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587683200,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_reg",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_off",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_get_fst",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/reset/core.c:__device_reset",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683200,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 933
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588995264,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_reg",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended",
        "drivers/acpi/device_pm.c:fix_up_power_if_applicable",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_off",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_get_fst",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/reset/core.c:__device_reset",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588995264,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1135
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589285760,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_reg",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended",
        "drivers/acpi/device_pm.c:fix_up_power_if_applicable",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_off",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_get_fst",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/reset/core.c:__device_reset",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589285760,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589592672,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_reg",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended",
        "drivers/acpi/device_pm.c:fix_up_power_if_applicable",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/device_pm.c:acpi_device_set_power",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_bus_get_power_flags",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:processor_physically_present",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_core.c:map_mat_entry",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_off",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_generate_interrupt",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/fan_core.c:acpi_fan_get_fst",
        "drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/reset/core.c:__device_reset",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589592672,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1172
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497564152,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497564152,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096108,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_turn_off_unused_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096108,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585011457,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_turn_off_unused_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/nfit/core.c:__acpi_nfit_notify",
        "drivers/acpi/nfit/core.c:acpi_nfit_add",
        "drivers/acpi/nfit/core.c:acpi_nfit_ctl",
        "drivers/acpi/nfit/core.c:acpi_label_read",
        "drivers/acpi/nfit/core.c:acpi_label_write",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011457,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585190038,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190038,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```

```json
{
  "name": "acpi_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296198,
      "name": "acpi_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:163",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_execute_simple_method",
        "drivers/acpi/utils.c:acpi_evaluate_ost",
        "drivers/acpi/utils.c:acpi_get_physical_device_location",
        "drivers/acpi/utils.c:acpi_evaluate_reference",
        "drivers/acpi/utils.c:acpi_evaluate_integer",
        "drivers/acpi/device_sysfs.c:acpi_device_setup_files",
        "drivers/acpi/bus.c:acpi_run_osc",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/processor_core.c:acpi_get_ioapic_id",
        "drivers/acpi/processor_pdc.c:early_init_pdc",
        "drivers/acpi/ec.c:acpi_ec_event_processor",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:__acpi_power_on",
        "drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute_method",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/fan.c:fan_get_cur_state",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_psd",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/xen/xen-acpi-pad.c:acpi_pad_notify",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296198,
      "name": "acpi_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list * external_params, struct acpi_buffer * return_buffer)
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
