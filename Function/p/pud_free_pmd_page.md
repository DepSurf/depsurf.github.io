# Function: <code>pud_free_pmd_page</code>

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
int pud_free_pmd_page(pud_t * pud)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344576,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:713",
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
      "addr": 18446744071579344576,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355936,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:742",
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
      "addr": 18446744071579355936,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383136,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:816",
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
      "addr": 18446744071579383136,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398608,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:803",
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
      "addr": 18446744071579398608,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401920,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:799",
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
      "addr": 18446744071579401920,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411296,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:802",
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
      "addr": 18446744071579411296,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411920,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:802",
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
      "addr": 18446744071579411920,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415072,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:794",
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
      "addr": 18446744071579415072,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477952,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:794",
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
      "addr": 18446744071579477952,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556496,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:803",
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
      "addr": 18446744071579556496,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663520,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:810",
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
      "addr": 18446744071579663520,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677664,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:802",
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
      "addr": 18446744071579677664,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711792,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:814",
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
      "addr": 18446744071579711792,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t * pudp, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490349728,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/arm64/mm/mmu.c:1019",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490349728,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pud_free_pmd_page",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1091",
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282776320,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/radix_pgtable.c:1123",
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
      "addr": 13835058055282776320,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pud_free_pmd_page",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1091",
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397824,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:799",
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
      "addr": 18446744071579397824,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327232,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:799",
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
      "addr": 18446744071579327232,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397744,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:799",
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
      "addr": 18446744071579397744,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
```

```json
{
  "name": "pud_free_pmd_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406240,
      "name": "pud_free_pmd_page",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:799",
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
      "addr": 18446744071579406240,
      "name": "pud_free_pmd_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int pud_free_pmd_page(pud_t * pud)
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
<code>pud_t * pudp</code>
</li>
<li>
<b>Param removed. </b>
<code>pud_t * pud</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
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
int pud_free_pmd_page(pud_t * pud, long unsigned int addr)
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
