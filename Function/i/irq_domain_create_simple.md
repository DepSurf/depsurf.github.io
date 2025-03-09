# Function: <code>irq_domain_create_simple</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * irq_domain_create_simple(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_create_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:315",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591246967,
      "name": "irq_domain_create_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580049408,
      "name": "irq_domain_create_simple",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * irq_domain_create_simple(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_create_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:325",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592139944,
      "name": "irq_domain_create_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580183024,
      "name": "irq_domain_create_simple",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * irq_domain_create_simple(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_create_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:325",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/mfd/max8998-irq.c:max8998_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593910679,
      "name": "irq_domain_create_simple.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580331376,
      "name": "irq_domain_create_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct irq_domain * irq_domain_create_simple(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548224,
      "name": "irq_domain_create_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:349",
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
      "addr": 18446744071580548224,
      "name": "irq_domain_create_simple",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_domain_create_simple(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580620912,
      "name": "irq_domain_create_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:356",
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
      "addr": 18446744071580620912,
      "name": "irq_domain_create_simple",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_domain_create_simple(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685856,
      "name": "irq_domain_create_simple",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:356",
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
      "addr": 18446744071580685856,
      "name": "irq_domain_create_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct irq_domain * irq_domain_create_simple(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops * ops, void * host_data)
```
</details>
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
