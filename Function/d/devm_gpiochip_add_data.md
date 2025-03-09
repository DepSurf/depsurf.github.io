# Function: <code>devm_gpiochip_add_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583501968,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1308",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501968,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583641600,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641600,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583680944,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1381",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583680944,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583936416,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1412",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936416,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584136272,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1520",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136272,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584221904,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1537",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584221904,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584410576,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1556",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584410576,
      "name": "devm_gpiochip_add_data",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584546928,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546928,
      "name": "devm_gpiochip_add_data",
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496735032,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-pl061.c:pl061_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496735032,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230024440,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_register",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe",
        "drivers/pinctrl/sh-pfc/gpio.c:sh_pfc_register_gpiochip",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-pl061.c:pl061_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-twl6040.c:gpo_twl6040_probe",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230024440,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290826928,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290826928,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275489842,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275489842,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503856,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503856,
      "name": "devm_gpiochip_add_data",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584441984,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584441984,
      "name": "devm_gpiochip_add_data",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498592,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498592,
      "name": "devm_gpiochip_add_data",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```

```json
{
  "name": "devm_gpiochip_add_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584604864,
      "name": "devm_gpiochip_add_data",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1565",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604864,
      "name": "devm_gpiochip_add_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int devm_gpiochip_add_data(struct device * dev, struct gpio_chip * chip, void * data)
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
