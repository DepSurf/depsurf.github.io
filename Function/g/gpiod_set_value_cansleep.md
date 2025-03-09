# Function: <code>gpiod_set_value_cansleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583196304,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1727",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196304,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583497328,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2734",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583497328,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583637472,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2943",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583637472,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583677440,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2950",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677440,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583932080,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3268",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932080,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123968,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3459",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123968,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208208,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3707",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208208,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584396704,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3796",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584396704,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532512,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532512,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4563",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220586,
      "name": "gpiod_set_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585204048,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3387",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387020,
      "name": "gpiod_set_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585360544,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3364",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591329425,
      "name": "gpiod_set_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585244176,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3423",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592352188,
      "name": "gpiod_set_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585699760,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3544",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214028,
      "name": "gpiod_set_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071586866976,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588013744,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3614",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/tty/serial/serial_core.c:uart_set_rs485_config",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588013744,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588288400,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3655",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/tty/serial/serial_core.c:uart_set_rs485_config",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588288400,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588582144,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3848",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/tty/serial/serial_core.c:uart_set_rs485_config",
        "drivers/tty/serial/serial_core.c:uart_set_rs485_config",
        "drivers/tty/serial/serial_core.c:uart_set_rs485_config",
        "drivers/tty/serial/serial_core.c:uart_set_rs485_config",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts",
        "drivers/nvmem/core.c:nvmem_access_with_keepouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588582144,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496718952,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496718952,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230008212,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230008212,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290805120,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290805120,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275476698,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff",
        "drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275476698,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584489440,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489440,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584427568,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427568,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484176,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484176,
      "name": "gpiod_set_value_cansleep",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void gpiod_set_value_cansleep(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584590320,
      "name": "gpiod_set_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4150",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_unprepare",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_prepare",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/regulator/core.c:regulator_ena_gpio_ctrl",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_device.c:mdio_device_reset",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/i2c/i2c-core-base.c:set_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590320,
      "name": "gpiod_set_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
