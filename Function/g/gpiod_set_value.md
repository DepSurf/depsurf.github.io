# Function: <code>gpiod_set_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583196448,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1521",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196448,
      "name": "gpiod_set_value",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583497664,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2479",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583497664,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583637808,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2669",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583637808,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583677152,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2666",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677152,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583931936,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2940",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931936,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123888,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3132",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123888,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208128,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208128,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3385",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/net/phy/mdio_device.c:mdio_device_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411733,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584396768,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532432,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532432,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4145",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221121,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585204640,
      "name": "gpiod_set_value",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2969",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387754,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585361296,
      "name": "gpiod_set_value",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2946",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591330064,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585244848,
      "name": "gpiod_set_value",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2995",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592352949,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071585700528,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3116",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214815,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071586867888,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3186",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596205487,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588015328,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3227",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596730524,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588289936,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3420",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597638895,
      "name": "gpiod_set_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588583632,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496718848,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496718848,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230008100,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/ata/sata_highbank.c:ecx_transmit_led_message",
        "drivers/ata/sata_highbank.c:ecx_transmit_led_message",
        "drivers/ata/sata_highbank.c:ecx_transmit_led_message",
        "drivers/ata/sata_highbank.c:ecx_led_cycle_clock",
        "drivers/ata/sata_highbank.c:ecx_led_cycle_clock",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230008100,
      "name": "gpiod_set_value",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290804976,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290804976,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275476610,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/gpio-restart.c:gpio_restart_notify",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275476610,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584489360,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489360,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584427488,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427488,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484096,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484096,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void gpiod_set_value(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_set_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584590240,
      "name": "gpiod_set_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_gpio_gate_disable",
        "drivers/clk/clk-gpio.c:clk_gpio_gate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590240,
      "name": "gpiod_set_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
