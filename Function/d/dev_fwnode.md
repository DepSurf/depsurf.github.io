# Function: <code>dev_fwnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_fwnode",
      "external": false,
      "loc": "drivers/base/property.c:180",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_fwnode",
      "external": false,
      "loc": "drivers/base/property.c:185",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_fwnode",
      "external": false,
      "loc": "drivers/base/property.c:185",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585029909,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:183",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties"
      ],
      "caller_func": [
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029632,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585452629,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:190",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452288,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585697301,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:251",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695456,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585827605,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825744,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586061237,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/devcon.c:device_fwnode_match",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060160,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586209125,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208048,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586972549,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972064,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587058245,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057760,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586942085,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_bus_match",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941552,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587506405,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_bus_match",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:devprop_gpiochip_set_names",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-acpi.c:pci_set_acpi_fwnode",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/net/phy/phy_device.c:device_phy_find_device",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587505920,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588834021,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:20",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_bus_match",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-acpi.c:pci_set_acpi_fwnode",
        "drivers/dma/lgm/lgm-dma.c:ldma_cfg_init",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/net/phy/phy_device.c:device_phy_find_device",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/mmc/core/host.c:mmc_of_parse",
        "drivers/hte/hte.c:hte_ts_get",
        "net/ethernet/eth.c:device_get_ethdev_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588831472,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499013896,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/irqchip/irq-sni-exiu.c:exiu_acpi_probe",
        "drivers/irqchip/irq-sni-exiu.c:exiu_acpi_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499012288,
      "name": "dev_fwnode",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231577520,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231575880,
      "name": "dev_fwnode",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292175872,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292173280,
      "name": "dev_fwnode",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276382838,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276381428,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585969333,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968256,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585818597,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585817520,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586159141,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158064,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct fwnode_handle * dev_fwnode(struct device * dev)
```

```json
{
  "name": "dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586267845,
      "name": "dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:21",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_mac_address",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/mmc/core/host.c:mmc_of_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266768,
      "name": "dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct fwnode_handle * dev_fwnode(struct device * dev)
```
</details>
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct fwnode_handle * dev_fwnode(struct device * dev)
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
