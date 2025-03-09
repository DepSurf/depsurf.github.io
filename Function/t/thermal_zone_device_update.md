# Function: <code>thermal_zone_device_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585682096,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:560",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:emul_temp_store",
        "drivers/thermal/thermal_core.c:passive_store"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:emul_temp_store",
        "drivers/thermal/thermal_core.c:passive_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585682096,
      "name": "thermal_zone_device_update.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071585682480,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void thermal_zone_device_update(struct thermal_zone_device * tz)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586081040,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:560",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:emul_temp_store",
        "drivers/thermal/thermal_core.c:passive_store",
        "drivers/thermal/thermal_core.c:trip_point_temp_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check",
        "drivers/thermal/thermal_core.c:emul_temp_store",
        "drivers/thermal/thermal_core.c:passive_store",
        "drivers/thermal/thermal_core.c:trip_point_temp_store",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586080416,
      "name": "thermal_zone_device_update.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071586080784,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586274853,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:408",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274400,
      "name": "thermal_zone_device_update.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071586274800,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586371989,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:467",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586371536,
      "name": "thermal_zone_device_update.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071586371936,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586836469,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:467",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836016,
      "name": "thermal_zone_device_update.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071586836416,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587134182,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:464",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128304,
      "name": "thermal_zone_device_update.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071587128720,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587312521,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:468",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309680,
      "name": "thermal_zone_device_update.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071587310096,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587583171,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587579824,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071587589745,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587580224,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587790289,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587783184,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071587793089,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587783584,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588637884,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:462",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631472,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071588631584,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588652096,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:549",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652096,
      "name": "thermal_zone_device_update",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588543572,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:538",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535136,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
    },
    {
      "addr": 18446744071591525445,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588536064,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589217684,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:485",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589209104,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 931
    },
    {
      "addr": 18446744071592635783,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071589210048,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590680381,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:487",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_core.c:thermal_zone_device_set_mode",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590673952,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071594519563,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071590674336,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592349123,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:494",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592343056,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592775761,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:489",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592769568,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593520341,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:538",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597762557,
      "name": "thermal_zone_device_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593518864,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500992100,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/thermal/of-thermal.c:of_thermal_set_mode",
        "drivers/thermal/armada_thermal.c:armada_overheat_isr_thread",
        "drivers/thermal/armada_thermal.c:armada_overheat_isr_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500988688,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446603336500989144,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233499980,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/thermal/of-thermal.c:of_thermal_set_mode",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_work",
        "drivers/thermal/armada_thermal.c:armada_overheat_isr_thread",
        "drivers/thermal/armada_thermal.c:armada_overheat_isr_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233495640,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 3233496100,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294465952,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/thermal/of-thermal.c:of_thermal_set_mode",
        "drivers/thermal/of-thermal.c:of_thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294451136,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 13835058055294451664,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277743876,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/thermal/of-thermal.c:of_thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277739484,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446743936277739854,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587421265,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587414160,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071587424065,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587414560,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587189473,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587182368,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071587192273,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587182768,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587746433,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739328,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071587749233,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587739728,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void thermal_zone_device_update(struct thermal_zone_device * tz, enum thermal_notify_event event)
```

```json
{
  "name": "thermal_zone_device_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587859633,
      "name": "thermal_zone_device_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_check",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:passive_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587852512,
      "name": "thermal_zone_device_update.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071587862433,
      "name": "thermal_zone_device_update.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587852928,
      "name": "thermal_zone_device_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<code>enum thermal_notify_event event</code>
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
