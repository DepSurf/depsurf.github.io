# Function: <code>apic_update_vector</code>

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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219488,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:132",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219488,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231616,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:133",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231616,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255312,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:134",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255312,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579269328,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269328,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271696,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271696,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300352,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300352,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305840,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305840,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307920,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307920,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579356272,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356272,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419328,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419328,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502032,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502032,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514192,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514192,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542816,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:142",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542816,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270400,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270400,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205744,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205744,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271600,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271600,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```

```json
{
  "name": "apic_update_vector",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277456,
      "name": "apic_update_vector",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:131",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277456,
      "name": "apic_update_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
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
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void apic_update_vector(struct irq_data * irqd, unsigned int newvec, unsigned int newcpu)
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
