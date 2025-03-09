# Function: <code>fwnode_property_read_u32_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_u32_array(struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584423264,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:502",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u32_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584423264,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int fwnode_property_read_u32_array(struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758000,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:509",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_u32_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758000,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int fwnode_property_read_u32_array(struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584948224,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:509",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_property_read_u32_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584948224,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int fwnode_property_read_u32_array(struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585030854,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:522",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585030816,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585453622,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:531",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585453584,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585695797,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:592",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695952,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585826085,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826240,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586061765,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/soundwire/mipi_disco.c:sdw_slave_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_slave_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_slave_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_slave_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586061728,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586209653,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209616,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973157,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973120,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587058864,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587058816,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586942704,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942656,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587507024,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506976,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588832224,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:343",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832160,
      "name": "fwnode_property_read_u32_array",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590332944,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:350",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332864,
      "name": "fwnode_property_read_u32_array",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590652960,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:354",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590652880,
      "name": "fwnode_property_read_u32_array",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591013104,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:354",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591013024,
      "name": "fwnode_property_read_u32_array",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499014820,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_enable_quirk_socionext_synquacer",
        "drivers/irqchip/irq-sni-exiu.c:exiu_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499014688,
      "name": "fwnode_property_read_u32_array",
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231578232,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231578140,
      "name": "fwnode_property_read_u32_array",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292176648,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292176560,
      "name": "fwnode_property_read_u32_array",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276383428,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276383316,
      "name": "fwnode_property_read_u32_array",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585969861,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585969824,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585819125,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819088,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586159669,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159632,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int fwnode_property_read_u32_array(const struct fwnode_handle * fwnode, const char * propname, u32 * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_u32_array",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586268373,
      "name": "fwnode_property_read_u32_array",
      "external": true,
      "loc": "drivers/base/property.c:317",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_property_read_u32_array"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_get_default_pattern",
        "drivers/leds/led-core.c:led_get_default_pattern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268336,
      "name": "fwnode_property_read_u32_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
