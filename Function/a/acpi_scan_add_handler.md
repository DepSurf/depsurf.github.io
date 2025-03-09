# Function: <code>acpi_scan_add_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563402,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:96",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/int340x_thermal.c:acpi_int340x_thermal_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563402,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583885309,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:97",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583885309,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024423,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:98",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024423,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596589864,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:92",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079120,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602917901,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:93",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348976,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603089899,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:93",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569984,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604892059,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:93",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667296,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604998157,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:94",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867472,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605035388,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:94",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003344,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609324022,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:93",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585704912,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612394697,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:93",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/x86/s2idle.c:acpi_s2idle_setup",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827088,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614536794,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:91",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/x86/s2idle.c:acpi_s2idle_setup",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585706128,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615487964,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:88",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/x86/s2idle.c:acpi_s2idle_setup",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188096,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617290292,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:89",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/x86/s2idle.c:acpi_s2idle_setup",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424176,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628004949,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:88",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/x86/s2idle.c:acpi_s2idle_setup",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588680320,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619770389,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:87",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/x86/s2idle.c:acpi_s2idle_setup",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968080,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622077413,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:87",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/x86/s2idle.c:acpi_s2idle_setup",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589265536,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511115580,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:94",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_amba.c:acpi_amba_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497413712,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604940362,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:94",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947024,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604907705,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:94",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584855824,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605017976,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:94",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954928,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```

```json
{
  "name": "acpi_scan_add_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605039568,
      "name": "acpi_scan_add_handler",
      "external": true,
      "loc": "drivers/acpi/scan.c:94",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/acpi_processor.c:acpi_processor_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_init",
        "drivers/acpi/acpi_apd.c:acpi_apd_init",
        "drivers/acpi/acpi_pnp.c:acpi_pnp_init",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init",
        "drivers/acpi/container.c:acpi_container_init",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init",
        "drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061104,
      "name": "acpi_scan_add_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler * handler)
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
