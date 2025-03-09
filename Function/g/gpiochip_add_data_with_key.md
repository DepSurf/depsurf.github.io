# Function: <code>gpiochip_add_data_with_key</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583933840,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1115",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933840,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1230",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137198,
      "name": "gpiochip_add_data_with_key.cold.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071584133712,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2555
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1253",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223006,
      "name": "gpiochip_add_data_with_key.cold.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071584219296,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2602
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1263",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412515,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071584408032,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2531
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548971,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071584543712,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3213
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
int gpiochip_add_data_with_key(struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1643",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib-devres.c:devm_gpiochip_add_data_with_key",
        "drivers/gpio/gpio-msic.c:platform_msic_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585222212,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071585217088,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1695
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
int gpiochip_add_data_with_key(struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:572",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpio-msic.c:platform_msic_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591388898,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071585368368,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2022
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
int gpiochip_add_data_with_key(struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:570",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591331279,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071585252432,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2337
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
int gpiochip_add_data_with_key(struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:592",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592354428,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071585708400,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2177
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
int gpiochip_add_data_with_key(struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:593",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594216600,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071586876784,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2507
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
int gpiochip_add_data_with_key(struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:650",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596205731,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588025984,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2849
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
int gpiochip_add_data_with_key(struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:703",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596730790,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588300288,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2778
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
int gpiochip_add_data_with_key(struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:811",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597639160,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588593712,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2676
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496731552,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496731552,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3476
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230021276,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data",
        "drivers/gpio/gpio-htc-egpio.c:egpio_probe",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe",
        "drivers/mfd/sm501.c:sm501_gpio_register_chip",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe",
        "sound/soc/soc-ac97.c:snd_soc_new_ac97_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230021276,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3164
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290823088,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290823088,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3828
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275487234,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275487234,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2608
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505899,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071584500640,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3213
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584444027,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071584438768,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3213
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584500635,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071584495376,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3213
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
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1267",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606907,
      "name": "gpiochip_add_data_with_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071584601648,
      "name": "gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3213
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip * chip, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```
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
