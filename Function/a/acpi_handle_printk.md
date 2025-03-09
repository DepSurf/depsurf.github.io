# Function: <code>acpi_handle_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583542676,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:498",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542676,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863617,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:495",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863617,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002693,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:495",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002693,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584051936,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:495",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_eject_request",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584051936,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584318848,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:496",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/sleep.c:acpi_s2idle_wake",
        "drivers/acpi/sleep.c:acpi_s2idle_wake",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_eject_request",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584318848,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584539152,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:496",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539152,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584636368,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:496",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636368,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584836192,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:483",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584836192,
      "name": "acpi_handle_printk",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584971920,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:483",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971920,
      "name": "acpi_handle_printk",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:487",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/sleep.c:lpi_check_constraints",
        "drivers/acpi/sleep.c:lpi_check_constraints",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670264,
      "name": "acpi_handle_printk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585669072,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585792880,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:483",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/device_pm.c:__acpi_device_wakeup_enable",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585792880,
      "name": "acpi_handle_printk",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672592,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:463",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluation_failure_warn",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/device_pm.c:__acpi_device_wakeup_enable",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/ac.c:acpi_ac_get_state",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672592,
      "name": "acpi_handle_printk",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152160,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:477",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluation_failure_warn",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/device_pm.c:__acpi_device_wakeup_enable",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152160,
      "name": "acpi_handle_printk",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385056,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:477",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluation_failure_warn",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/device_pm.c:__acpi_device_wakeup_enable",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385056,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588634736,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:515",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluation_failure_warn",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/device_pm.c:__acpi_device_wakeup_enable",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_tie_nondev_subnodes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_check_constraints",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588634736,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922480,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:515",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluation_failure_warn",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/device_pm.c:__acpi_device_wakeup_enable",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_tie_nondev_subnodes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/thermal.c:acpi_thermal_trips_update",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922480,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221472,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:587",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_register_ioapic",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluation_failure_warn",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/utils.c:acpi_get_subsystem_id",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/device_pm.c:__acpi_device_wakeup_enable",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/mipi-disco-img.c:init_csi2_port",
        "drivers/acpi/mipi-disco-img.c:init_csi2_port",
        "drivers/acpi/mipi-disco-img.c:init_csi2_port",
        "drivers/acpi/mipi-disco-img.c:init_csi2_port",
        "drivers/acpi/mipi-disco-img.c:init_csi2_port",
        "drivers/acpi/mipi-disco-img.c:extract_crs_csi2_conn_info",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/dock.c:handle_dock",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_free_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_allocate",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/power.c:acpi_device_sleep_wake",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_data_add_buffer_props",
        "drivers/acpi/property.c:acpi_tie_nondev_subnodes",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/ac.c:acpi_ac_resume",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/thermal.c:acpi_thermal_adjust_trip",
        "drivers/acpi/thermal.c:update_trip_devices",
        "drivers/acpi/thermal.c:update_trip_devices",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221472,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497385944,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:483",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497385944,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_handle_printk",
      "external": false,
      "loc": "include/linux/acpi.h:960",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_handle_printk",
      "external": false,
      "loc": "include/linux/acpi.h:960",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_handle_printk",
      "external": false,
      "loc": "include/linux/acpi.h:960",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584919488,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:483",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919488,
      "name": "acpi_handle_printk",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584825360,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:483",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584825360,
      "name": "acpi_handle_printk",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584923504,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:483",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923504,
      "name": "acpi_handle_printk",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```

```json
{
  "name": "acpi_handle_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585029648,
      "name": "acpi_handle_printk",
      "external": true,
      "loc": "drivers/acpi/utils.c:483",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/acpi/utils.c:acpi_evaluate_dsm",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_lck",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/utils.c:acpi_evaluate_ej0",
        "drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/bus.c:acpi_bus_notify",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_ids_walk",
        "drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:dock_notify",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029648,
      "name": "acpi_handle_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_handle_printk(const char * level, acpi_handle handle, const char * fmt, void (anon))
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
