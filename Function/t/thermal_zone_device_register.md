# Function: <code>thermal_zone_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585691760,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1795",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/power/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691760,
      "name": "thermal_zone_device_register.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2414
    },
    {
      "addr": 18446744071585694176,
      "name": "thermal_zone_device_register",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586088240,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1803",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/power/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586088240,
      "name": "thermal_zone_device_register.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2432
    },
    {
      "addr": 18446744071586090672,
      "name": "thermal_zone_device_register",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586278528,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1143",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586278528,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1582
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
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586375184,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1181",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375184,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
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
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586839632,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1177",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839632,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1511
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
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587131920,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1175",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131920,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1538
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
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587312784,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1180",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312784,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1541
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
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587588144,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587586656,
      "name": "thermal_zone_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1474
    },
    {
      "addr": 18446744071587589843,
      "name": "thermal_zone_device_register.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587588144,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587793187,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587788992,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
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
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1223",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588639588,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588636832,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1291",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:psy_register_thermal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582437,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588653536,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1232",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591525564,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588542352,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1184",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592635963,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071589216384,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1392
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
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1187",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594519696,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071590679120,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1368
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
struct thermal_zone_device * thermal_zone_device_register(const char * type, int ntrips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592349232,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1352",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592349232,
      "name": "thermal_zone_device_register",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int ntrips, int mask, void * devdata, struct thermal_zone_device_ops * ops, const struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592775872,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1372",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592775872,
      "name": "thermal_zone_device_register",
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500990912,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/thermal/of-thermal.c:of_parse_thermal_zones",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500990912,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233498740,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:of_parse_thermal_zones",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233498740,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294464368,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:of_parse_thermal_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294464368,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2004
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277742836,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:of_parse_thermal_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277742836,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1282
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424163,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587419968,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192371,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587188176,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587749331,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587745136,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int trips, int mask, void * devdata, struct thermal_zone_device_ops * ops, struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```

```json
{
  "name": "thermal_zone_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_zone_device_register",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1235",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587862531,
      "name": "thermal_zone_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587858336,
      "name": "thermal_zone_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ntrips</code>
</li>
<li>
<b>Param removed. </b>
<code>int trips</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct thermal_zone_params * tzp</code> ➡️ <code>const struct thermal_zone_params * tzp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct thermal_zone_device * thermal_zone_device_register(const char * type, int ntrips, int mask, void * devdata, struct thermal_zone_device_ops * ops, const struct thermal_zone_params * tzp, int passive_delay, int polling_delay)
```
</details>
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
