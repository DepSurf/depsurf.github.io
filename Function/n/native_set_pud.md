# Function: <code>native_set_pud</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579256432,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:99",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256432,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255488,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:99",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255488,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579269008,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:99",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269008,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265681,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:108",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pud_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265616,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282448,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:110",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:110",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581267768,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:110",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282448,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293904,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602897332,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422144,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293904,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318896,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604694716,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581508013,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318896,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334096,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604794738,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617614,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334096,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579338304,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604820461,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688462,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338304,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579368000,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609158861,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905838,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368000,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367024,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612229459,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642905,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581957629,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367024,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371376,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614370213,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664665,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581983724,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371376,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432592,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615302189,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935808,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582285708,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432592,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501584,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617082454,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344803,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582763194,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501584,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598736,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627737403,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846086,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297149,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598736,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579611456,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619496705,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583061695,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516227,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611456,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641232,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621793537,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243232,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710246,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641232,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334208,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604734341,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657198,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334208,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581860,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009582,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579234352,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492070,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307283,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327389,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354420,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701962,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258163,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323774,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462513,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504531,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597176,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587642967,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648602,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334128,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604811908,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648510,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334128,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "native_set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579342480,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604824618,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714939,
      "name": "native_set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:111",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342480,
      "name": "native_set_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void native_set_pud(pud_t * pudp, pud_t pud)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
