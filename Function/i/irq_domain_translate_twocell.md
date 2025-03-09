# Function: <code>irq_domain_translate_twocell</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:995",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972237,
      "name": "irq_domain_translate_twocell.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579964672,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580014529,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014432,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580067574,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:999",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064176,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049942,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1023",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045920,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049873,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:990",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046784,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580179681,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1029",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179584,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580327638,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1031",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327504,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580543254,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1088",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543104,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580616783,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1069",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616608,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580681679,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1069",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681504,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491215896,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491215688,
      "name": "irq_domain_translate_twocell",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225231068,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225231068,
      "name": "irq_domain_translate_twocell",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284118800,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284118800,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271753472,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271753314,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579983265,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983168,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579921041,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920944,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579974801,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974704,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```

```json
{
  "name": "irq_domain_translate_twocell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580021425,
      "name": "irq_domain_translate_twocell",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:997",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_xlate_twocell"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021328,
      "name": "irq_domain_translate_twocell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int irq_domain_translate_twocell(struct irq_domain * d, struct irq_fwspec * fwspec, long unsigned int * out_hwirq, unsigned int * out_type)
```
</details>
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
