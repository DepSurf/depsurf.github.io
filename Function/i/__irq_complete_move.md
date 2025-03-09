# Function: <code>__irq_complete_move</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579194560,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:638",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_complete_move",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_complete_move",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194560,
      "name": "__irq_complete_move.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579193968,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:640",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193968,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207280,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:640",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207280,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203168,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:661",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203168,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218320,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:900",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218320,
      "name": "__irq_complete_move",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233600,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:916",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233600,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579258368,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:907",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258368,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272464,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:904",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272464,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274832,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:915",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274832,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273536,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:915",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273536,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208880,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:915",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208880,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274736,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:915",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274736,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```

```json
{
  "name": "__irq_complete_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276208,
      "name": "__irq_complete_move",
      "external": false,
      "loc": "arch/x86/kernel/apic/vector.c:915",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276208,
      "name": "__irq_complete_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __irq_complete_move(struct irq_cfg * cfg, unsigned int vector)
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
