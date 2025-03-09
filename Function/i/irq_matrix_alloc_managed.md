# Function: <code>irq_matrix_alloc_managed</code>

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
int irq_matrix_alloc_managed(struct irq_matrix * m, unsigned int cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866544,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:244",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866544,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int irq_matrix_alloc_managed(struct irq_matrix * m, unsigned int cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900672,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:242",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900672,
      "name": "irq_matrix_alloc_managed",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948064,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948064,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986720,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986720,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036848,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036848,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580087600,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087600,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071008,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071008,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071696,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071696,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:286",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592140375,
      "name": "irq_matrix_alloc_managed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580205472,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:286",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593911149,
      "name": "irq_matrix_alloc_managed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580359424,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:286",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595990021,
      "name": "irq_matrix_alloc_managed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580582304,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:286",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596508132,
      "name": "irq_matrix_alloc_managed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580655216,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:286",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597405797,
      "name": "irq_matrix_alloc_managed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580720432,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005584,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005584,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944256,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944256,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579997120,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997120,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```

```json
{
  "name": "irq_matrix_alloc_managed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043968,
      "name": "irq_matrix_alloc_managed",
      "external": true,
      "loc": "kernel/irq/matrix.c:285",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043968,
      "name": "irq_matrix_alloc_managed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int irq_matrix_alloc_managed(struct irq_matrix * m, unsigned int cpu)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask * msk</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int * mapped_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int cpu</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int irq_matrix_alloc_managed(struct irq_matrix * m, const struct cpumask * msk, unsigned int * mapped_cpu)
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
