# Function: <code>power_supply_get_property</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585655520,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/power_supply_core.c:490",
      "file": "drivers/power/power_supply_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/charger-manager.c:is_full_charged",
        "drivers/power/charger-manager.c:is_full_charged",
        "drivers/power/charger-manager.c:charger_get_property",
        "drivers/power/charger-manager.c:charger_get_property",
        "drivers/power/charger-manager.c:charger_get_property",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/power/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585655520,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586054052,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/power_supply_core.c:490",
      "file": "drivers/power/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/power_supply_core.c:power_supply_read_temp",
        "drivers/power/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/power/charger-manager.c:charger_get_property",
        "drivers/power/charger-manager.c:charger_get_property",
        "drivers/power/charger-manager.c:charger_get_property",
        "drivers/power/charger-manager.c:is_full_charged",
        "drivers/power/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053808,
      "name": "power_supply_get_property.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586053840,
      "name": "power_supply_get_property",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586251796,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:490",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251552,
      "name": "power_supply_get_property.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586251584,
      "name": "power_supply_get_property",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586349316,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:579",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586349008,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586813796,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:617",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813472,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587107268,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:624",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107024,
      "name": "power_supply_get_property.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587107056,
      "name": "power_supply_get_property",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587285172,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:762",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587284928,
      "name": "power_supply_get_property.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587284960,
      "name": "power_supply_get_property",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587554644,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587554400,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587554432,
      "name": "power_supply_get_property",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587757972,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587757728,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587757760,
      "name": "power_supply_get_property",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588605844,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:845",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:cm_init_thermal_data",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:fullbatt_vchk",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online",
        "drivers/power/supply/charger-manager.c:is_batt_present",
        "drivers/power/supply/charger-manager.c:is_batt_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588603504,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588628852,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:864",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:cm_init_thermal_data",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online",
        "drivers/power/supply/charger-manager.c:is_batt_present",
        "drivers/power/supply/charger-manager.c:is_batt_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626880,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588513892,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:864",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online",
        "drivers/power/supply/charger-manager.c:is_batt_present",
        "drivers/power/supply/charger-manager.c:is_batt_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588511664,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589186884,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:887",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online",
        "drivers/power/supply/charger-manager.c:is_batt_present",
        "drivers/power/supply/charger-manager.c:is_batt_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592633132,
      "name": "power_supply_get_property.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589184496,
      "name": "power_supply_get_property",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590646092,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:1045",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:is_charging",
        "drivers/power/supply/charger-manager.c:is_charging",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online",
        "drivers/power/supply/charger-manager.c:is_batt_present",
        "drivers/power/supply/charger-manager.c:is_batt_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594516853,
      "name": "power_supply_get_property.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590642784,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592310788,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:1049",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:is_charging",
        "drivers/power/supply/charger-manager.c:is_charging",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online",
        "drivers/power/supply/charger-manager.c:is_batt_present",
        "drivers/power/supply/charger-manager.c:is_batt_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596308558,
      "name": "power_supply_get_property.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592307312,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592733344,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:1199",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_core.c:__power_supply_get_supplier_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:is_charging",
        "drivers/power/supply/charger-manager.c:is_charging",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online",
        "drivers/power/supply/charger-manager.c:is_batt_present",
        "drivers/power/supply/charger-manager.c:is_batt_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596837961,
      "name": "power_supply_get_property.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592733312,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593481200,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:1198",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_core.c:__power_supply_get_supplier_property",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:_cm_monitor",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:is_charging",
        "drivers/power/supply/charger-manager.c:is_charging",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online",
        "drivers/power/supply/charger-manager.c:is_batt_present",
        "drivers/power/supply/charger-manager.c:is_batt_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597762011,
      "name": "power_supply_get_property.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593481168,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500951340,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500950936,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336500951016,
      "name": "power_supply_get_property",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233466716,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:cm_get_battery_temperature",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:get_batt_uV",
        "drivers/power/supply/charger-manager.c:is_ext_pwr_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233466424,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3233466460,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294410532,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294410144,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 13835058055294410224,
      "name": "power_supply_get_property",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277713742,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277713464,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936277713520,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587398916,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398672,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587398704,
      "name": "power_supply_get_property",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587167124,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587166880,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587166912,
      "name": "power_supply_get_property",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587714116,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713872,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587713904,
      "name": "power_supply_get_property",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int power_supply_get_property(struct power_supply * psy, enum power_supply_property psp, union power_supply_propval * val)
```

```json
{
  "name": "power_supply_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587827172,
      "name": "power_supply_get_property",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:772",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp"
      ],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit",
        "drivers/power/supply/power_supply_core.c:power_supply_read_temp",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_show_property",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:charger_get_property",
        "drivers/power/supply/charger-manager.c:is_full_charged",
        "drivers/power/supply/charger-manager.c:is_full_charged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826928,
      "name": "power_supply_get_property.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587826960,
      "name": "power_supply_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
