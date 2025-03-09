# Function: <code>acpi_walk_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583711441,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:630",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711441,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584035860,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:630",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584035860,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584178018,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:630",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178018,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584246084,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:630",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246084,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584602613,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:630",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602613,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584828368,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828368,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584931724,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931724,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585134575,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585134575,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585270937,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585270937,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585976480,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_possible",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/char/hpet.c:hpet_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976480,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586099383,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_possible",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/char/hpet.c:hpet_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586099383,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585976265,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/char/hpet.c:hpet_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976265,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586464921,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/char/hpet.c:hpet_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586464921,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587717692,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/acpica/rsxface.c:acpi_get_vendor_resource",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/char/hpet.c:hpet_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717692,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589034688,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/acpica/rsxface.c:acpi_get_vendor_resource",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/char/hpet.c:hpet_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589034688,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325840,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/acpica/rsxface.c:acpi_get_vendor_resource",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/char/hpet.c:hpet_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325840,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589632656,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/mipi-disco-img.c:acpi_mipi_check_crs_csi2",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/acpica/rsxface.c:acpi_get_vendor_resource",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/char/hpet.c:hpet_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589632656,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497587584,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/qcom-irq-combiner.c:combiner_probe",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/irq.c:acpi_irq_get",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497587584,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585117401,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585117401,
      "name": "acpi_walk_resources",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585032713,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "drivers/hv/vmbus_drv.c:vmbus_acpi_add",
        "drivers/hv/vmbus_drv.c:vmbus_acpi_add",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032713,
      "name": "acpi_walk_resources",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585222521,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585222521,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```

```json
{
  "name": "acpi_walk_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585328681,
      "name": "acpi_walk_resources",
      "external": true,
      "loc": "drivers/acpi/acpica/rsxface.c:594",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/ec.c:ec_parse_device",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_link.c:acpi_pci_link_add",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/acpi/ioapic.c:handle_ioapic_add",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource",
        "arch/x86/pci/mmconfig-shared.c:find_mboard_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328681,
      "name": "acpi_walk_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char * name, acpi_walk_resource_callback user_function, void * context)
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
