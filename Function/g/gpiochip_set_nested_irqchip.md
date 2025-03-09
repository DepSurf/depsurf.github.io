# Function: <code>gpiochip_set_nested_irqchip</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583634256,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1591",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634256,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583673840,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1579",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673840,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929184,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1616",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929184,
      "name": "gpiochip_set_nested_irqchip",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584121072,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1723",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121072,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206960,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1709",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206960,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1736",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411559,
      "name": "gpiochip_set_nested_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584395648,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548175,
      "name": "gpiochip_set_nested_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584531296,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gc, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2065",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219266,
      "name": "gpiochip_set_nested_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585193120,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496707208,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496707208,
      "name": "gpiochip_set_nested_irqchip",
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230006628,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230006628,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290802928,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290802928,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275475328,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275475328,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505103,
      "name": "gpiochip_set_nested_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584488224,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584443231,
      "name": "gpiochip_set_nested_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584426352,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499839,
      "name": "gpiochip_set_nested_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584482960,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq)
```

```json
{
  "name": "gpiochip_set_nested_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_set_nested_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1759",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606111,
      "name": "gpiochip_set_nested_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584589056,
      "name": "gpiochip_set_nested_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, int parent_irq)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int parent_irq</code> ➡️ <code>unsigned int parent_irq</code>
</li>
</ul>
</details>
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
<code>struct gpio_chip * gpiochip</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip * gc, struct irq_chip * irqchip, unsigned int parent_irq)
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
