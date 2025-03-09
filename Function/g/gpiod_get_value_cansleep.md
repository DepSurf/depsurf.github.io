# Function: <code>gpiod_get_value_cansleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194080,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1679",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194080,
      "name": "gpiod_get_value_cansleep",
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583495424,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2689",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495424,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583635552,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2898",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583635552,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583675520,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2905",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675520,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583933216,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3176",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933216,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125072,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3367",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125072,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584208688,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3609",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208688,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584397200,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3698",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397200,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584533024,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533024,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585202040,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4465",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_ioctl"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220935,
      "name": "gpiod_get_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585204416,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585361129,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3289",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387568,
      "name": "gpiod_get_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585361072,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585244681,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3266",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591329878,
      "name": "gpiod_get_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585244624,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585700361,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3325",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592352763,
      "name": "gpiod_get_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585700304,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586867565,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3446",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214504,
      "name": "gpiod_get_value_cansleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071586867504,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588016096,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3516",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:lineevent_ioctl_unlocked",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016096,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290848,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3557",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:lineevent_ioctl_unlocked",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588290848,
      "name": "gpiod_get_value_cansleep",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588584544,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3750",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584544,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496709048,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496709048,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230008812,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro",
        "sound/soc/soc-jack.c:gpio_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230008812,
      "name": "gpiod_get_value_cansleep",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290805984,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290805984,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275477198,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275477198,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584489952,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489952,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584428080,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428080,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584484688,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484688,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int gpiod_get_value_cansleep(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_value_cansleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584590864,
      "name": "gpiod_get_value_cansleep",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib-sysfs.c:value_show",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent",
        "drivers/clk/clk-gpio.c:clk_sleeping_gpio_gate_is_prepared",
        "drivers/net/phy/fixed_phy.c:fixed_mdio_read",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590864,
      "name": "gpiod_get_value_cansleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
