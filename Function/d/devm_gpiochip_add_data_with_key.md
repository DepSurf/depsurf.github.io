# Function: <code>devm_gpiochip_add_data_with_key</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "devm_gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585223584,
      "name": "devm_gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib-devres.c:506",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
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
      "addr": 18446744071585223584,
      "name": "devm_gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "devm_gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585372096,
      "name": "devm_gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib-devres.c:504",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
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
      "addr": 18446744071585372096,
      "name": "devm_gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "devm_gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585256464,
      "name": "devm_gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib-devres.c:504",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
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
      "addr": 18446744071585256464,
      "name": "devm_gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "devm_gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585712320,
      "name": "devm_gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib-devres.c:504",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
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
      "addr": 18446744071585712320,
      "name": "devm_gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "devm_gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586881248,
      "name": "devm_gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib-devres.c:504",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881248,
      "name": "devm_gpiochip_add_data_with_key",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "devm_gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588031008,
      "name": "devm_gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib-devres.c:472",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588031008,
      "name": "devm_gpiochip_add_data_with_key",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "devm_gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588305184,
      "name": "devm_gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib-devres.c:417",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588305184,
      "name": "devm_gpiochip_add_data_with_key",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "devm_gpiochip_add_data_with_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588598576,
      "name": "devm_gpiochip_add_data_with_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib-devres.c:417",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_probe",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588598576,
      "name": "devm_gpiochip_add_data_with_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int devm_gpiochip_add_data_with_key(struct device * dev, struct gpio_chip * gc, void * data, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```
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
