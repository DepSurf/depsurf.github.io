# Function: <code>load_new_mm_cr3</code>

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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345488,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:104",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345488,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579357184,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:104",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357184,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384384,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:112",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384384,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399904,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:113",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399904,
      "name": "load_new_mm_cr3",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403216,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:113",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403216,
      "name": "load_new_mm_cr3",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413328,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:269",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413328,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413728,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:268",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413728,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416432,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:269",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416432,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479376,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:276",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479376,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558208,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:277",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558208,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665408,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:277",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665408,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579680381,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:281",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579714829,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:282",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399120,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:113",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399120,
      "name": "load_new_mm_cr3",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579328416,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:113",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328416,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399040,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:113",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399040,
      "name": "load_new_mm_cr3",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```

```json
{
  "name": "load_new_mm_cr3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407536,
      "name": "load_new_mm_cr3",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:113",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407536,
      "name": "load_new_mm_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
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
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void load_new_mm_cr3(pgd_t * pgdir, u16 new_asid, bool need_flush)
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
