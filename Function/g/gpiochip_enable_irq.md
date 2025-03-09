# Function: <code>gpiochip_enable_irq</code>

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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584197264,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3511",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197264,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3600",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584410944,
      "name": "gpiochip_enable_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584387872,
      "name": "gpiochip_enable_irq",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522736,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522736,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void gpiochip_enable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585196000,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4362",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585196000,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void gpiochip_enable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585353840,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3186",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585353840,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void gpiochip_enable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585237728,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3163",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237728,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void gpiochip_enable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585692768,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3222",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585692768,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void gpiochip_enable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586853296,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3343",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmask",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853296,
      "name": "gpiochip_enable_irq",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587997264,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3413",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmask",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997264,
      "name": "gpiochip_enable_irq",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271952,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3454",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmask",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271952,
      "name": "gpiochip_enable_irq",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564208,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3647",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmask",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564208,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496710856,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496710856,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229996728,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229996728,
      "name": "gpiochip_enable_irq",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290788800,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290788800,
      "name": "gpiochip_enable_irq",
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275465954,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275465954,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479664,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479664,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417792,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417792,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584474400,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584474400,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584580528,
      "name": "gpiochip_enable_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580528,
      "name": "gpiochip_enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void gpiochip_enable_irq(struct gpio_chip * chip, unsigned int offset)
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
