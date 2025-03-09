# Function: <code>acpi_create_platform_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583597198,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:43",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_default_enumeration",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597198,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583920436,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:43",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920436,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584061382,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:61",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061382,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584123008,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:63",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123008,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584394336,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:63",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584394336,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584617136,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:63",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617136,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584715632,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:64",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715632,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 703
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584918016,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:61",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917376,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071584918098,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584918016,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585053824,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:99",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053184,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071585053906,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585053824,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585756912,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:99",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_generic_device_attach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585756272,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071585756994,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585756912,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585876032,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:97",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_generic_device_attach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585875392,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071591436795,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585876032,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585753712,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:97",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_generic_device_attach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753072,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071591377453,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585753712,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586236432,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:97",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_generic_device_attach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235792,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071592413021,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586236432,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, const struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:97",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_generic_device_attach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594280408,
      "name": "acpi_create_platform_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071587474512,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, const struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588741856,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:97",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_generic_device_attach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588741856,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, const struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:110",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_generic_device_attach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596746104,
      "name": "acpi_create_platform_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589030176,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, const struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:110",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_generic_device_attach",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597654752,
      "name": "acpi_create_platform_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589334736,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497458896,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:99",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497458896,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446603336497459528,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584985184,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:99",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984544,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071584985266,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584985184,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584900768,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:99",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584900128,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071584900850,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584900768,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585005408,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:99",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585004768,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071585005490,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585005408,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```

```json
{
  "name": "acpi_create_platform_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585111584,
      "name": "acpi_create_platform_device",
      "external": true,
      "loc": "drivers/acpi/acpi_platform.c:99",
      "file": "drivers/acpi/acpi_platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/acpi_apd.c:acpi_apd_create_device",
        "drivers/acpi/dptf/int340x_thermal.c:int340x_thermal_handler_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110944,
      "name": "acpi_create_platform_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071585111666,
      "name": "acpi_create_platform_device.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585111584,
      "name": "acpi_create_platform_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct property_entry * properties</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct property_entry * properties</code> ➡️ <code>const struct property_entry * properties</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct platform_device * acpi_create_platform_device(struct acpi_device * adev, struct property_entry * properties)
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
