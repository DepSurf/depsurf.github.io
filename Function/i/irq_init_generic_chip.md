# Function: <code>irq_init_generic_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579760923,
      "name": "irq_init_generic_chip",
      "external": false,
      "loc": "kernel/irq/generic-chip.c:205",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579783844,
      "name": "irq_init_generic_chip",
      "external": false,
      "loc": "kernel/irq/generic-chip.c:205",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579810740,
      "name": "irq_init_generic_chip",
      "external": false,
      "loc": "kernel/irq/generic-chip.c:205",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579808841,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:204",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809808,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579842998,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:213",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843968,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579876241,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877744,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579923297,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924800,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579961651,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963136,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580011411,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012896,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580060821,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062864,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580042645,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044640,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580043493,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:215",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045504,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580176223,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:215",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178272,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580324413,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:218",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326016,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580539645,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:218",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541424,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580613045,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:218",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614800,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580677416,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:218",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679616,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491208784,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491212696,
      "name": "irq_init_generic_chip",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225227748,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225229304,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284115244,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284118448,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271749988,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271752530,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980147,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981632,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917955,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919440,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579971683,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973168,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```

```json
{
  "name": "irq_init_generic_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580018851,
      "name": "irq_init_generic_chip",
      "external": true,
      "loc": "kernel/irq/generic-chip.c:214",
      "file": "kernel/irq/generic-chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_alloc_generic_chip"
      ],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_alloc_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019856,
      "name": "irq_init_generic_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic * gc, const char * name, int num_ct, unsigned int irq_base, void * reg_base, irq_flow_handler_t handler)
```
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
