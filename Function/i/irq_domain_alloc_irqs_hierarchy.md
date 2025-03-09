# Function: <code>irq_domain_alloc_irqs_hierarchy</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579810863,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1368",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815568,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579845023,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1369",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850960,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878942,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1253",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884672,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579925998,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1253",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931728,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579964190,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1290",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970128,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580013950,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019936,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580069006,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1294",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069888,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050558,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1407",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052112,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050590,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1374",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052176,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580184174,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1414",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184656,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580332606,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1417",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333184,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580548702,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1477",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549760,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580622129,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1456",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623168,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687073,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1456",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688112,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491214960,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491222896,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225230460,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225237588,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271752704,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271759098,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579982686,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988672,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579920462,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926448,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579974222,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980208,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_hierarchy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020846,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_parent",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_populate_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026848,
      "name": "irq_domain_alloc_irqs_hierarchy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int irq_domain_alloc_irqs_hierarchy(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```
</details>
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
