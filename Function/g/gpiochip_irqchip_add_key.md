# Function: <code>gpiochip_irqchip_add_key</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool nested, struct lock_class_key * lock_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583630160,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1752",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630160,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool nested, struct lock_class_key * lock_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668832,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1740",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668832,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922688,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1887",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922688,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1994",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136609,
      "name": "gpiochip_irqchip_add_key.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584116144,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2017",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222241,
      "name": "gpiochip_irqchip_add_key.cold.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584199744,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2081",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411032,
      "name": "gpiochip_irqchip_add_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584388896,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548033,
      "name": "gpiochip_irqchip_add_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584529680,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int gpiochip_irqchip_add_key(struct gpio_chip * gc, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2750",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219232,
      "name": "gpiochip_irqchip_add_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585190864,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496705592,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496705592,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230005348,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230005348,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290793680,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290793680,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275474146,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275474146,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504961,
      "name": "gpiochip_irqchip_add_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584486608,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584443089,
      "name": "gpiochip_irqchip_add_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584424736,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499697,
      "name": "gpiochip_irqchip_add_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584481344,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
```

```json
{
  "name": "gpiochip_irqchip_add_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_irqchip_add_key",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2408",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605969,
      "name": "gpiochip_irqchip_add_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584587440,
      "name": "gpiochip_irqchip_add_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int gpiochip_irqchip_add_key(struct gpio_chip * gpiochip, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool nested, struct lock_class_key * lock_key)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool threaded</code>
</li>
<li>
<b>Param added. </b>
<code>struct lock_class_key * request_key</code>
</li>
<li>
<b>Param removed. </b>
<code>bool nested</code>
</li>
</ul>
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
<code>struct gpio_chip * gpiochip</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip * gc, struct irq_chip * irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key * lock_key, struct lock_class_key * request_key)
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
