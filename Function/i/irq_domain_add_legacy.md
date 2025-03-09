# Function: <code>irq_domain_add_legacy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765968,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:229",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765968,
      "name": "irq_domain_add_legacy",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788704,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788704,
      "name": "irq_domain_add_legacy",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815824,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:220",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815824,
      "name": "irq_domain_add_legacy",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814192,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:356",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814192,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849120,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:357",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849120,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882864,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:359",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882864,
      "name": "irq_domain_add_legacy",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579930640,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:359",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930640,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969008,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:359",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969008,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018816,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018816,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067120,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:346",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067120,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049792,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:356",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049792,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049936,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:358",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049936,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183232,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:368",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183232,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331632,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:368",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331632,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548544,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:392",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548544,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621520,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:399",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621520,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686464,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:399",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686464,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491221416,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491221416,
      "name": "irq_domain_add_legacy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225236228,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/tzic.c:tzic_init_dt",
        "drivers/irqchip/irq-hip04.c:hip04_of_init",
        "drivers/irqchip/irq-omap-intc.c:omap_init_irq_legacy",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225236228,
      "name": "irq_domain_add_legacy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284123680,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/i8259.c:i8259_init",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284123680,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271757876,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271757876,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987552,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987552,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925328,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925328,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979088,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979088,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct irq_domain * irq_domain_add_legacy(struct device_node * of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_add_legacy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025728,
      "name": "irq_domain_add_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025728,
      "name": "irq_domain_add_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
