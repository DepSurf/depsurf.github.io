# Function: <code>device_set_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void device_set_node(struct device * dev, struct fwnode_handle * fwnode)
```

```json
{
  "name": "device_set_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587440496,
      "name": "device_set_node",
      "external": true,
      "loc": "drivers/base/core.c:4798",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440496,
      "name": "device_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void device_set_node(struct device * dev, struct fwnode_handle * fwnode)
```

```json
{
  "name": "device_set_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757168,
      "name": "device_set_node",
      "external": true,
      "loc": "drivers/base/core.c:4837",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757168,
      "name": "device_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void device_set_node(struct device * dev, struct fwnode_handle * fwnode)
```

```json
{
  "name": "device_set_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590245440,
      "name": "device_set_node",
      "external": true,
      "loc": "drivers/base/core.c:5056",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590245440,
      "name": "device_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void device_set_node(struct device * dev, struct fwnode_handle * fwnode)
```

```json
{
  "name": "device_set_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590565600,
      "name": "device_set_node",
      "external": true,
      "loc": "drivers/base/core.c:5065",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590565600,
      "name": "device_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void device_set_node(struct device * dev, struct fwnode_handle * fwnode)
```

```json
{
  "name": "device_set_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590924000,
      "name": "device_set_node",
      "external": true,
      "loc": "drivers/base/core.c:5079",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590924000,
      "name": "device_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void device_set_node(struct device * dev, struct fwnode_handle * fwnode)
```
</details>
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
