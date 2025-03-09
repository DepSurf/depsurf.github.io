# Function: <code>acpi_walk_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583693415,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:567",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693415,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584017798,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:566",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017798,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584159766,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:566",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_core.c:acpi_set_processor_mapping",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159766,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584227171,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:589",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_check_duplicates",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227171,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584573022,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:589",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573022,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584798174,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584798174,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584900565,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584900565,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585103568,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585103568,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585239926,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239926,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585945742,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_fields",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945742,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068673,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_fields",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068673,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585945494,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_fields",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945494,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586433787,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_fields",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586433787,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587685014,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_fields",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685014,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993792,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_fields",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993792,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589284288,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_fields",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284288,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589591008,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/scan.c:acpi_scan_hot_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_control_setup",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_fields",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589591008,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497565124,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497565124,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585097044,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097044,
      "name": "acpi_walk_namespace",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585012393,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012393,
      "name": "acpi_walk_namespace",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585191510,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585191510,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```

```json
{
  "name": "acpi_walk_namespace",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585297670,
      "name": "acpi_walk_namespace",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:554",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_is_video_device",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_references",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/ioapic.c:acpi_ioapic_add",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297670,
      "name": "acpi_walk_namespace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void * context, void * * return_value)
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
