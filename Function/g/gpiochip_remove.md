# Function: <code>gpiochip_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583192912,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:400",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_remove",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_remove",
        "drivers/gpio/gpio-sx150x.c:sx150x_remove",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_remove",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_remove",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_remove",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583192912,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583494432,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1229",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494432,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633712,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1310",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633712,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673328,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1303",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673328,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928592,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1331",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928592,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584121472,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1438",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121472,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205760,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1468",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205760,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1487",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411539,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584394896,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548155,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584530544,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void gpiochip_remove(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1874",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219819,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585199024,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void gpiochip_remove(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:821",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386609,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585357504,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void gpiochip_remove(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:810",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328653,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585240304,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
void gpiochip_remove(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:832",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592351425,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585695728,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void gpiochip_remove(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:862",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594213286,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586862848,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void gpiochip_remove(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588008688,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:932",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588008688,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void gpiochip_remove(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588283952,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:963",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283952,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void gpiochip_remove(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588576992,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1044",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588576992,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496714624,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_remove",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_remove",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496714624,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230002980,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_remove",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_remove",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove",
        "drivers/gpio/gpio-omap.c:omap_gpio_remove",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-twl4030.c:gpio_twl4030_remove",
        "drivers/mfd/sm501.c:sm501_dev_remove",
        "drivers/mfd/sm501.c:sm501_dev_remove",
        "drivers/mfd/sm501.c:sm501_init_dev",
        "drivers/mfd/asic3.c:asic3_remove",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/tc6393xb.c:tc6393xb_remove",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "sound/soc/soc-ac97.c:snd_soc_free_ac97_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230002980,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290797920,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_remove",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290797920,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275471996,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_remove",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275471996,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505083,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584487472,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584443211,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584425600,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499819,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584482208,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void gpiochip_remove(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_remove",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1496",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpio_chip_release",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606091,
      "name": "gpiochip_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584588304,
      "name": "gpiochip_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip * gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip * chip</code>
</li>
</ul>
</details>
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
