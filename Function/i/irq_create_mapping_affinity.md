# Function: <code>irq_create_mapping_affinity</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain * domain, irq_hw_number_t hwirq, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_create_mapping_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051232,
      "name": "irq_create_mapping_affinity",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:657",
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
      "addr": 18446744071580051232,
      "name": "irq_create_mapping_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
unsigned int irq_create_mapping_affinity(struct irq_domain * domain, irq_hw_number_t hwirq, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_create_mapping_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051264,
      "name": "irq_create_mapping_affinity",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:659",
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
      "addr": 18446744071580051264,
      "name": "irq_create_mapping_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
unsigned int irq_create_mapping_affinity(struct irq_domain * domain, irq_hw_number_t hwirq, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_create_mapping_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183328,
      "name": "irq_create_mapping_affinity",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:682",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183328,
      "name": "irq_create_mapping_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
unsigned int irq_create_mapping_affinity(struct irq_domain * domain, irq_hw_number_t hwirq, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_create_mapping_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331744,
      "name": "irq_create_mapping_affinity",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:682",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331744,
      "name": "irq_create_mapping_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
unsigned int irq_create_mapping_affinity(struct irq_domain * domain, irq_hw_number_t hwirq, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_create_mapping_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580547760,
      "name": "irq_create_mapping_affinity",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:748",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547760,
      "name": "irq_create_mapping_affinity",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain * domain, irq_hw_number_t hwirq, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_create_mapping_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580620304,
      "name": "irq_create_mapping_affinity",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:729",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620304,
      "name": "irq_create_mapping_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
unsigned int irq_create_mapping_affinity(struct irq_domain * domain, irq_hw_number_t hwirq, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_create_mapping_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685248,
      "name": "irq_create_mapping_affinity",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:729",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq",
        "drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/tps6586x.c:tps6586x_irq_get_virq",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685248,
      "name": "irq_create_mapping_affinity",
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain * domain, irq_hw_number_t hwirq, const struct irq_affinity_desc * affinity)
```
</details>
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
