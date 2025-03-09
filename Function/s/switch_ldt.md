# Function: <code>switch_ldt</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579322241,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:98",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579346320,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:155",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579357947,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:156",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579385242,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:151",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579400695,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:152",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579403980,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:152",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
```

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078848,
      "name": "switch_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078848,
      "name": "switch_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
```

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081200,
      "name": "switch_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081200,
      "name": "switch_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
```

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088064,
      "name": "switch_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088064,
      "name": "switch_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
```

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111200,
      "name": "switch_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111200,
      "name": "switch_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
```

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579142624,
      "name": "switch_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142624,
      "name": "switch_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
```

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579186992,
      "name": "switch_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186992,
      "name": "switch_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
```

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191056,
      "name": "switch_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191056,
      "name": "switch_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
```

```json
{
  "name": "switch_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220304,
      "name": "switch_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220304,
      "name": "switch_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399884,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:152",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579329341,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:152",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399804,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:152",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "switch_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579408300,
      "name": "switch_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:152",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
void switch_ldt(struct mm_struct * prev, struct mm_struct * next)
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
