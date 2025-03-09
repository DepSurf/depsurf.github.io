# Function: <code>gpiochip_set_chained_irqchip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583191184,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:494",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe",
        "drivers/gpio/gpio-intel-mid.c:intel_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191184,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583494016,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1414",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/gpio/gpio-zx.c:zx_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583494016,
      "name": "gpiochip_set_chained_irqchip",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633344,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1574",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633344,
      "name": "gpiochip_set_chained_irqchip",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672960,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1562",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672960,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583928064,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1594",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928064,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584121104,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1701",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121104,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584205312,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1688",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205312,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584411439,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1715",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411439,
      "name": "gpiochip_set_chained_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584394464,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584548055,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548055,
      "name": "gpiochip_set_chained_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584530288,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496706288,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496706288,
      "name": "gpiochip_set_chained_irqchip",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230005900,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230005900,
      "name": "gpiochip_set_chained_irqchip",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290801328,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290801328,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275474602,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275474602,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584504983,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504983,
      "name": "gpiochip_set_chained_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584487216,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584443111,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584443111,
      "name": "gpiochip_set_chained_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584425344,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584499719,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499719,
      "name": "gpiochip_set_chained_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584481952,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
```

```json
{
  "name": "gpiochip_set_chained_irqchip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584605991,
      "name": "gpiochip_set_chained_irqchip",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1738",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605991,
      "name": "gpiochip_set_chained_irqchip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071584588048,
      "name": "gpiochip_set_chained_irqchip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler)
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
