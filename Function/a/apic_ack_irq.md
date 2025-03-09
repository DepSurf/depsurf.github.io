# Function: <code>apic_ack_irq</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235888,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:814",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235888,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259552,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:805",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259552,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273600,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:802",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273600,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276016,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:813",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276016,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579298876,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:811",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304688,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304524,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:856",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310160,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579311916,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:889",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312976,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360588,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:889",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579361840,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579418171,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:889",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424944,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501371,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:885",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508672,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513531,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:885",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520928,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579542011,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:907",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549744,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274720,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:813",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274720,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210064,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:813",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210064,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275920,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:813",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275920,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void apic_ack_irq(struct irq_data * irqd)
```

```json
{
  "name": "apic_ack_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281808,
      "name": "apic_ack_irq",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:813",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281808,
      "name": "apic_ack_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void apic_ack_irq(struct irq_data * irqd)
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
