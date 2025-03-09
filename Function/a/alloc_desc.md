# Function: <code>alloc_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_desc * alloc_desc(int irq, int node, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738320,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:144",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738320,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760064,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:166",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760064,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786496,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:342",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786496,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783968,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:357",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783968,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817344,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:355",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817344,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851088,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:372",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851088,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898080,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:372",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898080,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932896,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932896,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983024,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983024,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030896,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030896,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014816,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014816,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015264,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015264,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147376,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147376,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580292272,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292272,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502832,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:392",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502832,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:412",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574384,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
    },
    {
      "addr": 18446744071596506968,
      "name": "alloc_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:412",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580638624,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
    },
    {
      "addr": 18446744071597404633,
      "name": "alloc_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491168856,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491168856,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225195364,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225195364,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284068336,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284068336,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271721622,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271721622,
      "name": "alloc_desc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951760,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951760,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889648,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889648,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943296,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943296,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```

```json
{
  "name": "alloc_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990192,
      "name": "alloc_desc",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:387",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990192,
      "name": "alloc_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
<code>unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>const struct cpumask * affinity</code>
</li>
<li>
<b>Param reordered. </b>
<code>irq, node, owner</code> ➡️ <code>irq, node, flags, affinity, owner</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct irq_desc * alloc_desc(int irq, int node, unsigned int flags, const struct cpumask * affinity, struct module * owner)
```
</details>
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
