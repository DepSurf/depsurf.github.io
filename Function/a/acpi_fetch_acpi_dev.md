# Function: <code>acpi_fetch_acpi_dev</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * acpi_fetch_acpi_dev(acpi_handle handle)
```

```json
{
  "name": "acpi_fetch_acpi_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617290495,
      "name": "acpi_fetch_acpi_dev",
      "external": true,
      "loc": "drivers/acpi/scan.c:598",
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
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587423808,
      "name": "acpi_fetch_acpi_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * acpi_fetch_acpi_dev(acpi_handle handle)
```

```json
{
  "name": "acpi_fetch_acpi_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628005126,
      "name": "acpi_fetch_acpi_dev",
      "external": true,
      "loc": "drivers/acpi/scan.c:590",
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
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
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
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588679888,
      "name": "acpi_fetch_acpi_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * acpi_fetch_acpi_dev(acpi_handle handle)
```

```json
{
  "name": "acpi_fetch_acpi_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619770566,
      "name": "acpi_fetch_acpi_dev",
      "external": true,
      "loc": "drivers/acpi/scan.c:589",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_bus_scan",
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
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967648,
      "name": "acpi_fetch_acpi_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct acpi_device * acpi_fetch_acpi_dev(acpi_handle handle)
```

```json
{
  "name": "acpi_fetch_acpi_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622077590,
      "name": "acpi_fetch_acpi_dev",
      "external": true,
      "loc": "drivers/acpi/scan.c:589",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_bus_scan",
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
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/dock.c:docked_show",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_get_pci_dev",
        "drivers/acpi/pci_root.c:acpi_is_root_bridge",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_extract_power_resources",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_parse_string_ref",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_dead",
        "drivers/acpi/processor_driver.c:acpi_soft_cpu_online",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/thermal.c:bind_unbind_cdev_cb",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589265280,
      "name": "acpi_fetch_acpi_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct acpi_device * acpi_fetch_acpi_dev(acpi_handle handle)
```
</details>
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
