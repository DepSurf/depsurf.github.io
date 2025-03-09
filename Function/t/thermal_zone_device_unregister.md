# Function: <code>thermal_zone_device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679664,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1962",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/power/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679664,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586078384,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1970",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/power/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078384,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586273248,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1268",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273248,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586372608,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1307",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586372608,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586837040,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1306",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586837040,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587129360,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1304",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129360,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587310976,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587310976,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587581216,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1364",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587581216,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587784576,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587784576,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588635376,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1362",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588635376,
      "name": "thermal_zone_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    },
    {
      "addr": 18446744071588635952,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588659760,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1433",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:psy_register_thermal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588659760,
      "name": "thermal_zone_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071588660352,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588540784,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1375",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588540784,
      "name": "thermal_zone_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071588541376,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589215392,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1330",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589214800,
      "name": "thermal_zone_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    },
    {
      "addr": 18446744071592635922,
      "name": "thermal_zone_device_unregister.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071589215392,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590677968,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1333",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590677328,
      "name": "thermal_zone_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
    },
    {
      "addr": 18446744071594519655,
      "name": "thermal_zone_device_unregister.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071590677968,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592346544,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1367",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345840,
      "name": "thermal_zone_device_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071596309090,
      "name": "thermal_zone_device_unregister.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071592346544,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592772416,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1411",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592772416,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593523104,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1476",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593523104,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500983240,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/of-thermal.c:of_thermal_destroy_zones",
        "drivers/thermal/armada_thermal.c:armada_thermal_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500983240,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233497120,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/of-thermal.c:of_thermal_destroy_zones",
        "drivers/thermal/armada_thermal.c:armada_thermal_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233497120,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294453472,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/of-thermal.c:of_thermal_destroy_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294453472,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277740540,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/thermal/of-thermal.c:of_thermal_destroy_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277740540,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587415552,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415552,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587183760,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587183760,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587740720,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587740720,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void thermal_zone_device_unregister(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587853920,
      "name": "thermal_zone_device_unregister",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1374",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853920,
      "name": "thermal_zone_device_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
