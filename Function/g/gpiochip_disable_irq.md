# Function: <code>gpiochip_disable_irq</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197104,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3501",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197104,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3590",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584410925,
      "name": "gpiochip_disable_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584387712,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522592,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522592,
      "name": "gpiochip_disable_irq",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194816,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4352",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194816,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void gpiochip_disable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585353232,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3176",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585353232,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void gpiochip_disable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585236720,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3153",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236720,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void gpiochip_disable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585692048,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3212",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585692048,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void gpiochip_disable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586853072,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3333",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask",
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_mask",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853072,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void gpiochip_disable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996992,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3403",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask",
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_mask",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996992,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void gpiochip_disable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271680,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3444",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask",
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_mask",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271680,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void gpiochip_disable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563920,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3637",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask",
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_mask",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563920,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496710328,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496710328,
      "name": "gpiochip_disable_irq",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229996344,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229996344,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290788544,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290788544,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275465788,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275465788,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479520,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479520,
      "name": "gpiochip_disable_irq",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417648,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417648,
      "name": "gpiochip_disable_irq",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584474256,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584474256,
      "name": "gpiochip_disable_irq",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584580384,
      "name": "gpiochip_disable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3944",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580384,
      "name": "gpiochip_disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void gpiochip_disable_irq(struct gpio_chip * chip, unsigned int offset)
```
</details>
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
