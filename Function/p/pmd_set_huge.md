# Function: <code>pmd_set_huge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308624,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:609",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308624,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308352,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:595",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308352,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579323584,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:595",
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
      "addr": 18446744071579323584,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320960,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:658",
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
      "addr": 18446744071579320960,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344144,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:655",
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
      "addr": 18446744071579344144,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:676",
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
      "addr": 18446744071579356496,
      "name": "pmd_set_huge.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579355440,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
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
      "addr": 18446744071579383650,
      "name": "pmd_set_huge.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579382624,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:729",
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
      "addr": 18446744071579399123,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579398096,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:725",
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
      "addr": 18446744071579402435,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579401408,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:730",
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
      "addr": 18446744071579411808,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579410784,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:730",
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
      "addr": 18446744071591270326,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579411424,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:730",
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
      "addr": 18446744071591213086,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579414592,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:730",
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
      "addr": 18446744071592087872,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579477472,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:739",
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
      "addr": 18446744071593854785,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579555920,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:746",
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
      "addr": 18446744071595969515,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579662848,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:739",
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
      "addr": 18446744071596487119,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579677008,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:751",
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
      "addr": 18446744071597383741,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579711136,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int pmd_set_huge(pmd_t * pmdp, phys_addr_t phys, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490346720,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/arm64/mm/mmu.c:970",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/mmu.c:vmemmap_populate",
        "arch/arm64/mm/mmu.c:init_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490346720,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
  "name": "pmd_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1071",
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282776672,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/radix_pgtable.c:1147",
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
      "addr": 13835058055282776672,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
  "name": "pmd_set_huge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1071",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:725",
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
      "addr": 18446744071579398339,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579397312,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:725",
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
      "addr": 18446744071579327634,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579326768,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:725",
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
      "addr": 18446744071579398259,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579397232,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
```

```json
{
  "name": "pmd_set_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_set_huge",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:725",
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
      "addr": 18446744071579406755,
      "name": "pmd_set_huge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579405728,
      "name": "pmd_set_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<b>Param added. </b>
<code>phys_addr_t phys</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t * pmd</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
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
int pmd_set_huge(pmd_t * pmd, phys_addr_t addr, pgprot_t prot)
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
