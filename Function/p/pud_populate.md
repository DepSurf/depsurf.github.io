# Function: <code>pud_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579274848,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:112",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071580674907,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:112",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580804574,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:112",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361800,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:112",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274848,
      "name": "pud_populate.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275280,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:116",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071580789181,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:116",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580928490,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863268,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:116",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274080,
      "name": "pud_populate.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579290720,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:116",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071580853546,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:116",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996814,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:116",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077974,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:116",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289520,
      "name": "pud_populate.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579287589,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:118",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071580898689,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:118",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045668,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:118",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304427,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:118",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286512,
      "name": "pud_populate.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306597,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:130",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071581000800,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:130",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581156256,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:130",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869771,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:130",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304960,
      "name": "pud_populate.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318327,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:130",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071581134407,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:130",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299449,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:130",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248765,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:130",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317280,
      "name": "pud_populate.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579343495,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:137",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:137",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581210839,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:137",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383025,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:137",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491051,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:137",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
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
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579359143,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581286998,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494382,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589952022,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357248,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579363383,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581345718,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558894,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179556,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579361488,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591185164,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581542070,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769150,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197855,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591680517,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581585309,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817339,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692746,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
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
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579397656,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581607552,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581845244,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275628,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:101",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591211037,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071591275628,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579459880,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581874672,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933109,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582136500,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216327,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592084921,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071592216327,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579535807,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593969539,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071582272893,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342019,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582585901,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593995053,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534000,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071593969539,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071593995053,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596435644,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582625392,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071582764973,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843283,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583097936,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152736,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625392,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583152736,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596976388,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834480,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071582981363,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059702,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583307830,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363168,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582834480,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583363168,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pud_populate(struct mm_struct * mm, pud_t * pud, pmd_t * pmd)
```

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597904820,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583008928,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071583124480,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__pmd_alloc"
      ]
    },
    {
      "addr": 18446744071583241328,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables"
      ]
    },
    {
      "addr": 18446744071583515408,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:huge_pmd_share"
      ]
    },
    {
      "addr": 18446744071583599648,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:99",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008928,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583124480,
      "name": "pud_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071583241328,
      "name": "pud_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071583515408,
      "name": "pud_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071583599648,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490463736,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/arm64/include/asm/pgalloc.h:52",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:stage2_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492751428,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/arm64/include/asm/pgalloc.h:52",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492988308,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/arm64/include/asm/pgalloc.h:52",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503922420,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/arm64/include/asm/pgalloc.h:52",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
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
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282773388,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgalloc.h:115",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286110576,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgalloc.h:115",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297818088,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgalloc.h:115",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
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
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272734106,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/riscv/include/asm/pgalloc.h:32",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272896216,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/riscv/include/asm/pgalloc.h:32",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270897316,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/riscv/include/asm/pgalloc.h:32",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579359287,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581314566,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527630,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781844,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357392,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589490421,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581258125,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469347,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504486,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
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
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579359207,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581305766,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518942,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225252,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357312,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367639,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 0,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581369766,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583916,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275610,
      "name": "pud_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365744,
      "name": "pud_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void pud_populate(struct mm_struct * mm, pud_t * pud, pmd_t * pmd)
```
</details>
</li>
</ul>
