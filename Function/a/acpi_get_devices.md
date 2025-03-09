# Function: <code>acpi_get_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583693267,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:784",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_ecdt_probe",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693267,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584017642,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:783",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017642,
      "name": "acpi_get_devices",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584159610,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:783",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159610,
      "name": "acpi_get_devices",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226083,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:806",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_check_duplicates",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226083,
      "name": "acpi_get_devices",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584571264,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:806",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571264,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584796405,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584796405,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898796,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898796,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585101785,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585101785,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585238143,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238143,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585945431,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945431,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068362,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068362,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585945183,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945183,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586433476,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586433476,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587684673,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587684673,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993408,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993408,
      "name": "acpi_get_devices",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589283904,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283904,
      "name": "acpi_get_devices",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589590624,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_control_setup",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/gpu/drm/drm_privacy_screen_x86.c:detect_thinkpad_privacy_screen",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589590624,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497563960,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_get_rc_resources",
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497563960,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585095949,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095949,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585011298,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011298,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189727,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189727,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```

```json
{
  "name": "acpi_get_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585295887,
      "name": "acpi_get_devices",
      "external": true,
      "loc": "drivers/acpi/acpica/nsxfeval.c:771",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/resource.c:acpi_resource_consumer",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/acpi_processor.c:acpi_early_processor_osc",
        "drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc",
        "drivers/acpi/ec.c:acpi_ec_dsdt_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_init",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved",
        "arch/x86/pci/mmconfig-shared.c:is_acpi_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585295887,
      "name": "acpi_get_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_get_devices(const char * HID, acpi_walk_callback user_function, void * context, void * * return_value)
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
