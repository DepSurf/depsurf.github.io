# Function: <code>pmd_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358431,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:650",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579288806,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:650",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309013,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:650",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667464,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:650",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746789,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:650",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358431,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579365308,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:623",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579288816,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:623",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308737,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:623",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580777464,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:623",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580866005,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:623",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365308,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579383404,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:614",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579304336,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:614",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323969,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:614",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842240,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:614",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907973,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:614",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383404,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579291229,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:661",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579302066,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:661",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321330,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:661",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580887643,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:661",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953429,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:661",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291229,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579310972,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:625",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579323598,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:625",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344533,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:625",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580982115,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:625",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055173,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:625",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310972,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322436,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579334433,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356432,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116780,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193893,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:630",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322436,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346740,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:608",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579360977,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:608",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383585,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:608",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195548,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:608",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267069,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:608",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277173,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:608",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346740,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362443,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:609",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579375573,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:609",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399058,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:609",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581262845,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:609",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341643,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:609",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351622,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:609",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362443,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366683,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579379861,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402370,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321581,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400969,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411126,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366683,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579393790,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:611",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579411743,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:611",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420766,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:611",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516381,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:611",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597294,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:611",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_normal_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611238,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:611",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393790,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591677107,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412463,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419246,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561310,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643497,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658582,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591620515,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415583,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424014,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585432,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665000,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581680390,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592793764,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478463,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487628,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581852771,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933574,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581949670,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594693576,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557037,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579567555,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246194,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342517,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582359140,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596431628,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664083,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675771,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582733726,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843803,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582861444,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:547",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596972412,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678227,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579689643,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582952537,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060235,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583076948,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:542",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597900860,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712371,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724171,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134809,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241707,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583259204,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490349608,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:486",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490464092,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:486",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:__unmap_hyp_range",
        "virt/kvm/arm/mmu.c:unmap_stage2_range",
        "virt/kvm/arm/mmu.c:unmap_stage2_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492733748,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:486",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492810140,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:486",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282735604,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:863",
      "file": "arch/powerpc/mm/book3s64/hash_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pmdp_collapse_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282776956,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:863",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_free_pte_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_clear_huge",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pmdp_collapse_flush",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286081328,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:863",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286191452,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:863",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272722624,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:143",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272772710,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:143",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362587,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579375765,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398274,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581290429,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369817,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379974,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362587,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362507,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579375685,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398194,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281629,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361017,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371174,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362507,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void pmd_clear(pmd_t * pmdp)
```

```json
{
  "name": "pmd_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579370939,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579384165,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406690,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345469,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424906,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435062,
      "name": "pmd_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:597",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370939,
      "name": "pmd_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void pmd_clear(pmd_t * pmdp)
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
void pmd_clear(pmd_t * pmdp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pmd_clear(pmd_t * pmdp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pmd_clear(pmd_t * pmdp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pmd_clear(pmd_t * pmdp)
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
void pmd_clear(pmd_t * pmdp)
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
