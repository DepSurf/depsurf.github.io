# Function: <code>reserve_irq_vector_locked</code>

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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220672,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220672,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579232720,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:200",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232720,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579256368,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:201",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256368,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270400,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:198",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270400,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272768,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:198",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272768,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300160,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300160,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305664,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305664,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307760,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307760,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579356112,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356112,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419152,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419152,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502992,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502992,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515264,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515264,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543984,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:210",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543984,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271472,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:198",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271472,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206816,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:198",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206816,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272672,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:198",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272672,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```

```json
{
  "name": "reserve_irq_vector_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579278624,
      "name": "reserve_irq_vector_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:198",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278624,
      "name": "reserve_irq_vector_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void reserve_irq_vector_locked(struct irq_data * irqd)
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
void reserve_irq_vector_locked(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void reserve_irq_vector_locked(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void reserve_irq_vector_locked(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void reserve_irq_vector_locked(struct irq_data * irqd)
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
