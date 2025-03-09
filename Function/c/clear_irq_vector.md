# Function: <code>clear_irq_vector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579192830,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:253",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs"
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
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579193396,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:254",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs"
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
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579205268,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:254",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579204502,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:261",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219104,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:331",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219104,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231216,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:341",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231216,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579254912,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:332",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254912,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268928,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:329",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268928,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271296,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:329",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271296,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302432,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:330",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302432,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307776,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307776,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309776,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309776,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579358256,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358256,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579421648,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421648,
      "name": "clear_irq_vector",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505136,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505136,
      "name": "clear_irq_vector",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517408,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:334",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517408,
      "name": "clear_irq_vector",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546128,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:345",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546128,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270000,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:329",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270000,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205344,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:329",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205344,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271200,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:329",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271200,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
void clear_irq_vector(struct irq_data * irqd)
```

```json
{
  "name": "clear_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277040,
      "name": "clear_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:329",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277040,
      "name": "clear_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void clear_irq_vector(struct irq_data * irqd)
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
