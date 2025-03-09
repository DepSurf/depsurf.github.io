# Function: <code>assign_vector_locked</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219840,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:245",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219840,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231952,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:255",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231952,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255648,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:224",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255648,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579269680,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:221",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269680,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272048,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:221",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272048,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301184,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301184,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306592,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306592,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308672,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308672,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579357200,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357200,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420320,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420320,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503728,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503728,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516000,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516000,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544720,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:233",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544720,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270752,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:221",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270752,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206096,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:221",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206096,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271952,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:221",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271952,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```

```json
{
  "name": "assign_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277840,
      "name": "assign_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:221",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277840,
      "name": "assign_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
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
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int assign_vector_locked(struct irq_data * irqd, const struct cpumask * dest)
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
