# Function: <code>fwnode_property_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool fwnode_property_present(struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584421168,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:216",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584421168,
      "name": "fwnode_property_present",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool fwnode_property_present(struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584755152,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:221",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755152,
      "name": "fwnode_property_present",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool fwnode_property_present(struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584945376,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:221",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945376,
      "name": "fwnode_property_present",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fwnode_property_present(struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585033040,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:252",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/property.c:device_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585033040,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585456000,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:260",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/property.c:device_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456000,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585699552,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:321",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/property.c:device_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699552,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585828768,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585828768,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586063728,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/soundwire/mipi_disco.c:sdw_slave_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_slave_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_slave_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop",
        "drivers/soundwire/mipi_disco.c:sdw_master_read_prop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586063728,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586211616,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211616,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586972608,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972608,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587058304,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587058304,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586942144,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/base/property.c:device_property_present",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942144,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587506464,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/base/property.c:device_property_present",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506464,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588831504,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:45",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/base/property.c:device_property_present",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588831504,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590332096,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:52",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/base/property.c:device_property_present",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332096,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590652112,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:56",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/base/property.c:device_property_present",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590652112,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591012256,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:56",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/base/property.c:device_property_present",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-core.c:led_parse_fwnode_props",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591012256,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499017464,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/base/property.c:device_property_present",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499017464,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231580160,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_present",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_match",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231580160,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292179632,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_present",
        "drivers/base/property.c:device_property_present",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292179632,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276385274,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_present",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276385274,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585971824,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585971824,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585821088,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821088,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586161632,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161632,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool fwnode_property_present(const struct fwnode_handle * fwnode, const char * propname)
```

```json
{
  "name": "fwnode_property_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586270336,
      "name": "fwnode_property_present",
      "external": true,
      "loc": "drivers/base/property.c:46",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/base/property.c:device_property_present",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name",
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586270336,
      "name": "fwnode_property_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
