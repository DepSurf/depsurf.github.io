# Function: <code>assign_irq_vector_any_locked</code>

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
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579222922,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:270",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235166,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:280",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579258837,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:272",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579272929,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:269",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579275201,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:269",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int assign_irq_vector_any_locked(struct irq_data * irqd)
```

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301552,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:270",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:activate_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301552,
      "name": "assign_irq_vector_any_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int assign_irq_vector_any_locked(struct irq_data * irqd)
```

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306928,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:270",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:activate_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306928,
      "name": "assign_irq_vector_any_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int assign_irq_vector_any_locked(struct irq_data * irqd)
```

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309008,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:270",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309008,
      "name": "assign_irq_vector_any_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int assign_irq_vector_any_locked(struct irq_data * irqd)
```

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579357536,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:270",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357536,
      "name": "assign_irq_vector_any_locked",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int assign_irq_vector_any_locked(struct irq_data * irqd)
```

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420688,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:270",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420688,
      "name": "assign_irq_vector_any_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int assign_irq_vector_any_locked(struct irq_data * irqd)
```

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504112,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:270",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504112,
      "name": "assign_irq_vector_any_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int assign_irq_vector_any_locked(struct irq_data * irqd)
```

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516384,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:270",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516384,
      "name": "assign_irq_vector_any_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int assign_irq_vector_any_locked(struct irq_data * irqd)
```

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545104,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:281",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545104,
      "name": "assign_irq_vector_any_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579273905,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:269",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579209249,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:269",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579275105,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:269",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
  "name": "assign_irq_vector_any_locked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579280997,
      "name": "assign_irq_vector_any_locked",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:269",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int assign_irq_vector_any_locked(struct irq_data * irqd)
```
</details>
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
