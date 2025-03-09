# Function: <code>assign_irq_vector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int assign_irq_vector(int irq, struct apic_chip_data * data, const struct cpumask * mask)
```

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579193408,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:229",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193408,
      "name": "assign_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
int assign_irq_vector(int irq, struct apic_chip_data * data, const struct cpumask * mask)
```

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194016,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:230",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194016,
      "name": "assign_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1074
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
int assign_irq_vector(int irq, struct apic_chip_data * data, const struct cpumask * mask)
```

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205696,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:230",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205696,
      "name": "assign_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 997
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
int assign_irq_vector(int irq, struct apic_chip_data * data, const struct cpumask * mask, struct irq_data * irqdata)
```

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203328,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:235",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203328,
      "name": "assign_irq_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579221807,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:258",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579234170,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:268",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579257178,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:260",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579271237,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:257",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579273605,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:257",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579303733,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:258",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579308939,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:258",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579311126,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:258",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579359766,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:258",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579423304,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:258",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579506795,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:258",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579519065,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:258",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547879,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:269",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579272309,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:257",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579207653,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:257",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579273509,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:257",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579279477,
      "name": "assign_irq_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:257",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_data * irqdata</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int assign_irq_vector(int irq, struct apic_chip_data * data, const struct cpumask * mask, struct irq_data * irqdata)
```
</details>
</li>
</ul>
