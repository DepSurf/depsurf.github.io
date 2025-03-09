# Function: <code>fwnode_property_read_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_string(struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584421440,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:618",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_phy_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584421440,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int fwnode_property_read_string(struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584755872,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:626",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_phy_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755872,
      "name": "fwnode_property_read_string",
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
int fwnode_property_read_string(struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584946096,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:626",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_phy_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946096,
      "name": "fwnode_property_read_string",
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
int fwnode_property_read_string(struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585032502,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:606",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_phy_mode"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031200,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585455446,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:615",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_phy_mode"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585453968,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585697908,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:676",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696288,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585828164,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826576,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586062708,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062096,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586210596,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209984,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973956,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973488,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587059620,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059184,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586943460,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943024,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587507780,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/net/phy/phy_device.c:fwnode_get_phy_id",
        "drivers/leds/led-core.c:led_init_default_state_get",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587507344,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588834170,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:435",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/net/phy/phy_device.c:fwnode_get_phy_id",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/leds/led-core.c:led_init_default_state_get",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832656,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590335226,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:442",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/net/phy/phy_device.c:fwnode_get_phy_id",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/leds/led-core.c:led_init_default_state_get",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590333456,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590655274,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:446",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/net/phy/phy_device.c:fwnode_get_phy_id",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/leds/led-core.c:led_init_default_state_get",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590653472,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591015578,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:446",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_property_string",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/net/phy/phy_device.c:fwnode_get_phy_id",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/leds/led-core.c:led_init_default_state_get",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591013616,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499016052,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499015368,
      "name": "fwnode_property_read_string",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231578936,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231578580,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292177852,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292177168,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276384362,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276383840,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585970804,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970192,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585820068,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819456,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586160612,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160000,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int fwnode_property_read_string(const struct fwnode_handle * fwnode, const char * propname, const char * * val)
```

```json
{
  "name": "fwnode_property_read_string",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586269316,
      "name": "fwnode_property_read_string",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:device_property_read_string"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268704,
      "name": "fwnode_property_read_string",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * fwnode</code> ➡️ <code>const struct fwnode_handle * fwnode</code>
</li>
</ul>
</details>
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
