# Function: <code>__free_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irqaction * __free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743872,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1432",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:remove_irq",
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743872,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
struct irqaction * __free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766656,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1461",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766656,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
struct irqaction * __free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579793664,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1461",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793664,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
struct irqaction * __free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790704,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1475",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790704,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
struct irqaction * __free_irq(unsigned int irq, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824192,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1528",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824192,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857360,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1572",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857360,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904928,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1585",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904928,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941088,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1693",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941088,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991264,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991264,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046736,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1740",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046736,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029936,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1810",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029936,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030672,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1811",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030672,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163184,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1840",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163184,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309392,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1874",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309392,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580522208,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1866",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522208,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595136,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1872",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595136,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580659680,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1872",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659680,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491181048,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491181048,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225204524,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225204524,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284082528,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284082528,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271728062,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271728062,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960000,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960000,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897840,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897840,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951536,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951536,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
struct irqaction * __free_irq(struct irq_desc * desc, void * dev_id)
```

```json
{
  "name": "__free_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579997920,
      "name": "__free_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1685",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:free_irq",
        "kernel/irq/manage.c:remove_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997920,
      "name": "__free_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_desc * desc</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int irq</code>
</li>
</ul>
</details>
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
