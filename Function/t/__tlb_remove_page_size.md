# Function: <code>__tlb_remove_page_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580783219,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/memory.c:298",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771424,
      "name": "__tlb_remove_page_size.part.59",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071580776624,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580844727,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/memory.c:298",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841392,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580886768,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/memory.c:302",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886768,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580980912,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/memory.c:303",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980912,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581115728,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/memory.c:302",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115728,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256400,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:119",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256400,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331328,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331328,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390736,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390736,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587536,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587536,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633488,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633488,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655168,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655168,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581923360,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923360,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582330128,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:79",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330128,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct encoded_page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830400,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:118",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830400,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct encoded_page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583045792,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:118",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045792,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct encoded_page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227744,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:119",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:native_tlb_remove_table",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227744,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492796648,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492796648,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226611092,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:free_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226611092,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286166864,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286166864,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272764382,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272764382,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581359584,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359584,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581303296,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303296,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581350784,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350784,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```

```json
{
  "name": "__tlb_remove_page_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414720,
      "name": "__tlb_remove_page_size",
      "external": true,
      "loc": "mm/mmu_gather.c:66",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414720,
      "name": "__tlb_remove_page_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather * tlb, struct page * page, int page_size)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page * page</code> ➡️ <code>struct encoded_page * page</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
