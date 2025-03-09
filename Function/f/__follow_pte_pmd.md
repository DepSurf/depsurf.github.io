# Function: <code>__follow_pte_pmd</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580838144,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:3775",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838144,
      "name": "__follow_pte_pmd.isra.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, long unsigned int * start, long unsigned int * end, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883456,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4046",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883456,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 922
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, long unsigned int * start, long unsigned int * end, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976992,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4224",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976992,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, long unsigned int * start, long unsigned int * end, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112224,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4269",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112224,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1017
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581191344,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4059",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191344,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264144,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4108",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264144,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322928,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322928,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520976,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4498",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520976,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492729424,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492729424,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226560540,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226560540,
      "name": "__follow_pte_pmd.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286074928,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286074928,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272721352,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272721352,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291776,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291776,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236288,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236288,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282976,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282976,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```

```json
{
  "name": "__follow_pte_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346992,
      "name": "__follow_pte_pmd",
      "external": false,
      "loc": "mm/memory.c:4133",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:follow_pte_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346992,
      "name": "__follow_pte_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1022
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, long unsigned int * start, long unsigned int * end, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<code>struct mmu_notifier_range * range</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * end</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, address, start, end, ptepp, pmdpp, ptlp</code> ➡️ <code>mm, address, range, ptepp, pmdpp, ptlp</code>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __follow_pte_pmd(struct mm_struct * mm, long unsigned int address, struct mmu_notifier_range * range, pte_t * * ptepp, pmd_t * * pmdpp, spinlock_t * * ptlp)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
