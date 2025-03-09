# Function: <code>pgtable_pte_page_dtor</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399317,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581343876,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691812,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715138,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "fs/dax.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579408709,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2244",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540423,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2244",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909382,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2244",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930078,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2244",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2244",
      "file": "fs/dax.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pgtable_pte_page_dtor(struct page * page)
```

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579412280,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2249",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585514,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2249",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954538,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2249",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071581976916,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2249",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2249",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940800,
      "name": "pgtable_pte_page_dtor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void pgtable_pte_page_dtor(struct page * page)
```

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415434,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2257",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607760,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2257",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581980284,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2257",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    },
    {
      "addr": 18446744071582004931,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2257",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2257",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967424,
      "name": "pgtable_pte_page_dtor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void pgtable_pte_page_dtor(struct page * page)
```

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579478314,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2286",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874880,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2286",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582282417,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2286",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    },
    {
      "addr": 18446744071582307373,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2286",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2286",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270112,
      "name": "pgtable_pte_page_dtor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556861,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2364",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582273119,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2364",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582766484,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2364",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792627,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2364",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2364",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579663892,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765199,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583300908,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331218,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579678036,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2842",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981589,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2842",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583520084,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2842",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583550060,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2842",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:2842",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492749624,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493137136,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493161684,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224500640,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "arch/arm/mm/pgd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/pgd.c:pgd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3226581004,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282725840,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "arch/powerpc/mm/pgtable-frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable-frag.c:pte_fragment_free",
        "arch/powerpc/mm/pgtable-frag.c:pte_frag_destroy"
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
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272732962,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
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
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579395221,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312724,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660548,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683874,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579324949,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256436,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600629,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622466,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579395141,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303924,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651860,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675186,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgtable_pte_page_dtor",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579403653,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367892,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718293,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741798,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgtable_pte_page_dtor",
      "external": false,
      "loc": "include/linux/mm.h:1978",
      "file": "fs/dax.c",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void pgtable_pte_page_dtor(struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void pgtable_pte_page_dtor(struct page * page)
```
</details>
</li>
</ul>
