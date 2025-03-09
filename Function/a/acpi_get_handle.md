# Function: <code>acpi_get_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694385,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:80",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/i2c/i2c-core.c:acpi_i2c_find_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694385,
      "name": "acpi_get_handle",
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018806,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:80",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/i2c/i2c-core.c:acpi_i2c_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018806,
      "name": "acpi_get_handle",
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160774,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:80",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_ecdt_start",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/i2c/i2c-core.c:i2c_acpi_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160774,
      "name": "acpi_get_handle",
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228187,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:80",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228187,
      "name": "acpi_get_handle",
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584574160,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:80",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574160,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584799310,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799310,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584901701,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584901701,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585104738,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585104738,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585241096,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241096,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585946958,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/bus.c:acpi_bus_osc_support",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/property.c:acpi_add_nondev_subnodes",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946958,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586069889,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/bus.c:acpi_bus_osc_support",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/property.c:acpi_add_nondev_subnodes",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586069889,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585946707,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946707,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586435000,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_parse_resource",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586435000,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587686210,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/bus.c:acpi_bus_osc_negotiate_platform_control",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_parse_resource",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587686210,
      "name": "acpi_get_handle",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588997216,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/bus.c:acpi_bus_osc_negotiate_platform_control",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_parse_resource",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588997216,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
acpi_status acpi_get_handle(acpi_handle parent, const char * pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287712,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_bus_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/bus.c:acpi_bus_osc_negotiate_platform_control",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_parse_resource",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287712,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
acpi_status acpi_get_handle(acpi_handle parent, const char * pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589594480,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_device_dep",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/bus.c:acpi_bus_osc_negotiate_usb_control",
        "drivers/acpi/bus.c:acpi_bus_osc_negotiate_platform_control",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_set_pnp_ids",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/mipi-disco-img.c:parse_csi2_resource",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/property.c:acpi_parse_string_ref",
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_parse_resource",
        "drivers/iommu/intel/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594480,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497566300,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497566300,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585098098,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585098098,
      "name": "acpi_get_handle",
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585013434,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/nfit/core.c:acpi_nfit_add_dimm",
        "drivers/acpi/nfit/core.c:acpi_nfit_add_dimm",
        "drivers/acpi/nfit/core.c:acpi_nfit_add_dimm",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585013434,
      "name": "acpi_get_handle",
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585192680,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585192680,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```

```json
{
  "name": "acpi_get_handle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298840,
      "name": "acpi_get_handle",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfname.c:46",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/acpi/utils.c:acpi_has_method",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:acpi_init",
        "drivers/acpi/bus.c:sb_notify_work",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/scan.c:acpi_bus_get_ejd",
        "drivers/acpi/ec.c:acpi_ec_init",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/apei/apei-base.c:apei_osc_setup",
        "drivers/iommu/dmar.c:dmar_dev_scope_init",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298840,
      "name": "acpi_get_handle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>acpi_string pathname</code> ➡️ <code>const char * pathname</code>
</li>
</ul>
</details>
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle * ret_handle)
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
