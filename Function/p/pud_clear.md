# Function: <code>pud_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358400,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:610",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579289054,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:610",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308923,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:610",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667663,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:610",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746709,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:610",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800490,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:610",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358400,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579365277,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:583",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579289036,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:583",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308652,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:583",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580777768,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:583",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865925,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:583",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924058,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:583",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365277,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579383373,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579304556,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323884,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842513,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907893,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992402,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:574",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383373,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579291198,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:576",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579302284,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:576",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321244,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:576",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580888122,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:576",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953349,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:576",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039922,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:576",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291198,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579310941,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579323851,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344722,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580982492,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055093,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149849,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310941,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322405,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579334778,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356145,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117203,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193813,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293321,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:540",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322405,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346709,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:524",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579361322,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:524",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383327,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:524",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195981,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:524",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277093,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:524",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376345,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:524",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346709,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362412,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579375863,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398799,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263089,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351542,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487244,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362412,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366652,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579380151,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402111,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321825,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411046,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551660,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366652,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579393707,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579411487,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421464,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516627,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611142,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762082,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393707,
      "name": "pud_clear",
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591678134,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412102,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421907,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561542,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642895,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658502,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810169,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591621815,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415254,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424965,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585674,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664655,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581680310,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838597,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592795062,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478134,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488592,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581853013,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935798,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949590,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129446,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594694938,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556676,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579568602,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246389,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344794,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359044,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576242,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596432655,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663703,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676840,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582733919,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846075,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861332,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095130,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596973433,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677847,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690706,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582952735,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583061677,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583076836,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304973,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597901865,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711975,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725234,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135007,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243221,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259092,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583542845,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490349888,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:547",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:pud_free_pmd_page",
        "arch/arm64/mm/mmu.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490464148,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:547",
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
      "addr": 18446603336492734192,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:547",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492810076,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:547",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492988828,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:547",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282776428,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:911",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pud_clear_huge",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282843096,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:911",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286081660,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:911",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286191356,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:911",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
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
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272722866,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:51",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272772644,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:51",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272890634,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:51",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362556,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579376055,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398015,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581290673,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379894,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520396,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362556,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362476,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579375975,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397935,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281873,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371094,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511708,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362476,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
```

```json
{
  "name": "pud_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579370908,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579384455,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406431,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345713,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434982,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576764,
      "name": "pud_clear",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370908,
      "name": "pud_clear",
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
void pud_clear(pud_t * pudp)
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
void pud_clear(pud_t * pudp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pud_clear(pud_t * pudp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pud_clear(pud_t * pudp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pud_clear(pud_t * pudp)
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
void pud_clear(pud_t * pudp)
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
