# Function: <code>apic_update_irq_cfg</code>

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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218800,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:118",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218800,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579230896,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:119",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230896,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579254592,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:120",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254592,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268608,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268608,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270976,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270976,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299904,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299904,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305424,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305424,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307456,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307456,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355776,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355776,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418784,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418784,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502592,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502592,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514752,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071596483298,
      "name": "apic_update_irq_cfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:128",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543376,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
    },
    {
      "addr": 18446744071597379531,
      "name": "apic_update_irq_cfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579269680,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269680,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205024,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205024,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270880,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270880,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```

```json
{
  "name": "apic_update_irq_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276704,
      "name": "apic_update_irq_cfg",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:117",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276704,
      "name": "apic_update_irq_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
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
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void apic_update_irq_cfg(struct irq_data * irqd, unsigned int vector, unsigned int cpu)
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
