# Function: <code>irq_domain_add_simple</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765824,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:186",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:_gpiochip_irqchip_add",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765824,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788560,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:179",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:_gpiochip_irqchip_add",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788560,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815680,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:177",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815680,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814048,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:313",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814048,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848976,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:314",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848976,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:316",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886840,
      "name": "irq_domain_add_simple.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579882720,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:316",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933896,
      "name": "irq_domain_add_simple.cold.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579930512,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:316",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972493,
      "name": "irq_domain_add_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579968864,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022075,
      "name": "irq_domain_add_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580018672,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:303",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072537,
      "name": "irq_domain_add_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580066976,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:313",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304191,
      "name": "irq_domain_add_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580049264,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587222789,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:328",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591456265,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:328",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
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
  "name": "irq_domain_add_simple",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587787383,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:327",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592518663,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:327",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
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
  "name": "irq_domain_add_simple",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589134809,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:341",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594387579,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:341",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
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
  "name": "irq_domain_add_simple",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590679065,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:329",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590684171,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:329",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
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
  "name": "irq_domain_add_simple",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591020137,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:332",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591025227,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:332",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
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
  "name": "irq_domain_add_simple",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591364185,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:332",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591369275,
      "name": "irq_domain_add_simple",
      "external": false,
      "loc": "include/linux/irqdomain.h:332",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491221192,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491221192,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225236044,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-aspeed-vic.c:avic_of_init",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225236044,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284123376,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284123376,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271757712,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271757712,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990811,
      "name": "irq_domain_add_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579987408,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928587,
      "name": "irq_domain_add_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579925184,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982347,
      "name": "irq_domain_add_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579978944,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_add_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:318",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028987,
      "name": "irq_domain_add_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580025584,
      "name": "irq_domain_add_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct irq_domain * irq_domain_add_simple(struct device_node * of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
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
