# Function: <code>irq_domain_alloc_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579764976,
      "name": "irq_domain_alloc_descs",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:838",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764976,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789200,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:881",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789200,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579816320,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:907",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816320,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579814896,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1074",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814896,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850304,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1087",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850304,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct cpumask * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579884016,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:971",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884016,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931072,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:971",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931072,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579969488,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1008",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969488,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580019296,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019296,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580070973,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1012",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064800,
      "name": "irq_domain_alloc_descs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071580069728,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053234,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1036",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046816,
      "name": "irq_domain_alloc_descs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071580051872,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053372,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1003",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047536,
      "name": "irq_domain_alloc_descs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071580051936,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580185816,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1042",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180544,
      "name": "irq_domain_alloc_descs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071580184496,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580333708,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1044",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328656,
      "name": "irq_domain_alloc_descs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071580332976,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550605,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1101",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544560,
      "name": "irq_domain_alloc_descs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071580549520,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580623942,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1082",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618000,
      "name": "irq_domain_alloc_descs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071580622928,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580688944,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1082",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682896,
      "name": "irq_domain_alloc_descs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071580687872,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491222000,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491222000,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225236768,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225236768,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284124976,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284124976,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271758396,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271758396,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579988032,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988032,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579925808,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925808,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979568,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979568,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int irq_domain_alloc_descs(int virq, unsigned int cnt, irq_hw_number_t hwirq, int node, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "irq_domain_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580026208,
      "name": "irq_domain_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1010",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026208,
      "name": "irq_domain_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask * affinity</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct cpumask * affinity</code> ➡️ <code>const struct irq_affinity_desc * affinity</code>
</li>
</ul>
</details>
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
