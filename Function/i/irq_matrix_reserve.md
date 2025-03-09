# Function: <code>irq_matrix_reserve</code>

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
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866976,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:292",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866976,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:290",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901930,
      "name": "irq_matrix_reserve.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579901104,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949466,
      "name": "irq_matrix_reserve.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579948624,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988138,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579987280,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038266,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071580037408,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089034,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580088144,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304381,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580071456,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247223,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580072176,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:346",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592140425,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580206048,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:346",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593911197,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580360160,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580583088,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:346",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580583088,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580656000,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:346",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656000,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721216,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:346",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721216,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007002,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071580006144,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945674,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579944816,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998538,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579997680,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```

```json
{
  "name": "irq_matrix_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_matrix_reserve",
      "external": true,
      "loc": "kernel/irq/matrix.c:345",
      "file": "kernel/irq/matrix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045498,
      "name": "irq_matrix_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071580044560,
      "name": "irq_matrix_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void irq_matrix_reserve(struct irq_matrix * m)
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
void irq_matrix_reserve(struct irq_matrix * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void irq_matrix_reserve(struct irq_matrix * m)
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
