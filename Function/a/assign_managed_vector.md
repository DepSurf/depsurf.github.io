# Function: <code>assign_managed_vector</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221088,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:309",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221088,
      "name": "assign_managed_vector.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579233168,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:319",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233168,
      "name": "assign_managed_vector.isra.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579257760,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:311",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257760,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271840,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:308",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271840,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274208,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:308",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274208,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300736,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:309",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300736,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306160,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:313",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306160,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308240,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:313",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308240,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579356768,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:313",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356768,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419872,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:313",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419872,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503184,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:313",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503184,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515456,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:313",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515456,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544176,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:324",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544176,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272912,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:308",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272912,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208256,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:308",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208256,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274112,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:308",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274112,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_managed_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579280144,
      "name": "assign_managed_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:308",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280144,
      "name": "assign_managed_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int assign_managed_vector(struct irq_data * irqd, const struct cpumask * dest)
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
