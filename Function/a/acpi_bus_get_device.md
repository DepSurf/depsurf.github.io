# Function: <code>acpi_bus_get_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583560884,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:577",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_cpu_soft_notify",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560884,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882557,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:597",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_cpu_soft_notify",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882557,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021666,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:598",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021666,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596590053,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:596",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078560,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602918090,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:597",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/sleep.c:acpi_s2idle_wake",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346704,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603090088,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:598",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567696,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604892248,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:598",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665488,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604998347,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:599",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865600,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605035578,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:599",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001472,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609324222,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:598",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/sleep.c:lpi_check_constraints",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_resources_list_add",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704688,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612394897,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:600",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_resources_list_add",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826864,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614536998,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:592",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:docked_show",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705872,
      "name": "acpi_bus_get_device",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615488168,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:589",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:docked_show",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187856,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511115752,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:599",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_get_rc_resources",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster",
        "drivers/perf/xgene_pmu.c:acpi_pmu_dev_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497413576,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604940552,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:599",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946944,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604907895,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:599",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584855744,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605018166,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:599",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584953056,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```

```json
{
  "name": "acpi_bus_get_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605039758,
      "name": "acpi_bus_get_device",
      "external": true,
      "loc": "drivers/acpi/scan.c:599",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/device_pm.c:acpi_bus_can_wakeup",
        "drivers/acpi/device_pm.c:acpi_bus_power_manageable",
        "drivers/acpi/device_pm.c:acpi_bus_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:show_docked",
        "drivers/acpi/pci_root.c:acpi_pci_find_root",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059232,
      "name": "acpi_bus_get_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```
</details>
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
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device * * device)
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
