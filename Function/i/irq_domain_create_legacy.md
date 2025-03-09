# Function: <code>irq_domain_create_legacy</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_domain * irq_domain_create_legacy(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_legacy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049822,
      "name": "irq_domain_create_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:368",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049408,
      "name": "irq_domain_create_legacy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_domain * irq_domain_create_legacy(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_legacy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049966,
      "name": "irq_domain_create_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:370",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049536,
      "name": "irq_domain_create_legacy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_domain * irq_domain_create_legacy(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_legacy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580183262,
      "name": "irq_domain_create_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:380",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183152,
      "name": "irq_domain_create_legacy",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_domain * irq_domain_create_legacy(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_legacy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580331662,
      "name": "irq_domain_create_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:380",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331536,
      "name": "irq_domain_create_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_domain * irq_domain_create_legacy(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_legacy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580548574,
      "name": "irq_domain_create_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:404",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548416,
      "name": "irq_domain_create_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_domain * irq_domain_create_legacy(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_legacy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580621550,
      "name": "irq_domain_create_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:411",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620784,
      "name": "irq_domain_create_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_domain * irq_domain_create_legacy(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "irq_domain_create_legacy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580686494,
      "name": "irq_domain_create_legacy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:411",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685728,
      "name": "irq_domain_create_legacy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct irq_domain * irq_domain_create_legacy(struct fwnode_handle * fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops * ops, void * host_data)
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
