# Function: <code>irq_create_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765136,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:461",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:_gpiochip_irqchip_add",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765136,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789376,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:457",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:_gpiochip_irqchip_add",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789376,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816496,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:480",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816496,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815072,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:618",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815072,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850480,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:632",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850480,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884192,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:634",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884192,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931248,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:634",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931248,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969648,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:648",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969648,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019456,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019456,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068624,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:635",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068624,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580054344,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:397",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585359185,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:397",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587205812,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:397",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587272373,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:397",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587289839,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:397",
      "file": "drivers/mfd/wm831x-auxadc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587310855,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:397",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342277,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:397",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588576092,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:397",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580055048,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:402",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585239871,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:402",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587091748,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:402",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587160728,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:402",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587177167,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:402",
      "file": "drivers/mfd/wm831x-auxadc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587197992,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:402",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225317,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:402",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588459644,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:402",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580187508,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:399",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585695247,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:399",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663828,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:399",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587737375,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:399",
      "file": "drivers/mfd/wm831x-auxadc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587759942,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:399",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587789813,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:399",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589127772,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:399",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580336062,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:413",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586863362,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:413",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589010452,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:413",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589082963,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:413",
      "file": "drivers/mfd/wm831x-auxadc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589105160,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:413",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589137413,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:413",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590576940,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:413",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588009369,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590538116,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:401",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590616099,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:401",
      "file": "drivers/mfd/wm831x-auxadc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590641961,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:401",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590682597,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:401",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592233631,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:401",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588288066,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590865396,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590957187,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/mfd/wm831x-auxadc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590982818,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591023685,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592657887,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588581186,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591208900,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591301043,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/mfd/wm831x-auxadc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591326786,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591367733,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593403055,
      "name": "irq_create_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:404",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491222216,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_to_irq",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpio-davinci.c:gpio_to_irq_banked",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_to_irq",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_to_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/tc3589x.c:tc3589x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491222216,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225236972,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_to_irq",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_to_irq",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_to_irq",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_to_irq",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_msi_setup_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/tc3589x.c:tc3589x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/memory/omap-gpmc.c:gpmc_get_client_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225236972,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284125264,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_setup_device",
        "arch/powerpc/sysdev/mpic.c:mpic_request_ipis",
        "arch/powerpc/sysdev/mpic_u3msi.c:u3msi_setup_msi_irqs",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_smp_probe",
        "arch/powerpc/sysdev/xive/common.c:xive_smp_probe",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_request",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init",
        "arch/powerpc/platforms/powernv/pci.c:pnv_setup_msi_irqs",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq",
        "drivers/tty/hvc/hvsi.c:hvsi_console_init",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/tc3589x.c:tc3589x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284125264,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271758548,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/tc3589x.c:tc3589x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271758548,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988192,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988192,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925968,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925968,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979728,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979728,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_create_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026368,
      "name": "irq_create_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:650",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026368,
      "name": "irq_create_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
unsigned int irq_create_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
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
