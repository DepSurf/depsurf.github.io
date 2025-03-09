# Function: <code>pmd_free_pte_page</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pmd_free_pte_page(pmd_t * pmd)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579344696,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:740",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342144,
      "name": "pmd_free_pte_page.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071579344784,
      "name": "pmd_free_pte_page",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579356352,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:788",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356352,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383520,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:859",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383520,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398992,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:846",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398992,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402304,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:842",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402304,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411680,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:845",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411680,
      "name": "pmd_free_pte_page",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412400,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:847",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412400,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415520,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:839",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415520,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579478400,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:839",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478400,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556976,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:848",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556976,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664016,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:855",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664016,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678160,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:847",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678160,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712304,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:859",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_range_noflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712304,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int pmd_free_pte_page(pmd_t * pmdp, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490349844,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/arm64/mm/mmu.c:1000",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:pud_free_pmd_page"
      ],
      "caller_func": [
        "arch/arm64/mm/mmu.c:pud_free_pmd_page",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490345520,
      "name": "pmd_free_pte_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446603336490349640,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_free_pte_page",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1095",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282776864,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/radix_pgtable.c:1170",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282776864,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_free_pte_page",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1095",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398208,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:842",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398208,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327536,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:842",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327536,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398128,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:842",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398128,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```

```json
{
  "name": "pmd_free_pte_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406624,
      "name": "pmd_free_pte_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:842",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406624,
      "name": "pmd_free_pte_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int pmd_free_pte_page(pmd_t * pmd)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
</ul>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pmd_t * pmdp</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t * pmd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pmd_free_pte_page(pmd_t * pmd, long unsigned int addr)
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
