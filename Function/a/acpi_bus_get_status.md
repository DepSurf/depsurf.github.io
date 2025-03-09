# Function: <code>acpi_bus_get_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583558271,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:108",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583558271,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879898,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:112",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/i2c/i2c-core.c:acpi_i2c_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879898,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018952,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:112",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/i2c/i2c-core.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018952,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584072000,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:112",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072000,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584341680,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:139",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341680,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584561200,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:140",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561200,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584658512,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:109",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658512,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584858800,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858800,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584994672,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584994672,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585693792,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/tty/serdev/core.c:acpi_serdev_check_resources",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693792,
      "name": "acpi_bus_get_status.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    },
    {
      "addr": 18446744071585694112,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585816016,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/tty/serdev/core.c:acpi_serdev_check_resources",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585816016,
      "name": "acpi_bus_get_status.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071585816336,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585696528,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:94",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696528,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586176848,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176848,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587412176,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:97",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587412176,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668016,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:98",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668016,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588955744,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:95",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588955744,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589253040,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:95",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589253040,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497401448,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/perf/xgene_pmu.c:acpi_pmu_dev_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497401448,
      "name": "acpi_bus_get_status",
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584938752,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584938752,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584847552,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584847552,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584946256,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946256,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int acpi_bus_get_status(struct acpi_device * device)
```

```json
{
  "name": "acpi_bus_get_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585052432,
      "name": "acpi_bus_get_status",
      "external": true,
      "loc": "drivers/acpi/bus.c:96",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/scan.c:acpi_device_hotplug",
        "drivers/acpi/scan.c:acpi_scan_bus_check",
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585052432,
      "name": "acpi_bus_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int acpi_bus_get_status(struct acpi_device * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_bus_get_status(struct acpi_device * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_bus_get_status(struct acpi_device * device)
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
