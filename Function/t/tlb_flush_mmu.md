# Function: <code>tlb_flush_mmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580666496,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/memory.c:261",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:tlb_finish_mmu"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666496,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580776559,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/memory.c:265",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:tlb_finish_mmu"
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
      "addr": 18446744071580776512,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580841327,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/memory.c:265",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:tlb_finish_mmu"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841280,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580886695,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/memory.c:265",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:arch_tlb_finish_mmu"
      ],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886608,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580980839,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/memory.c:266",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:arch_tlb_finish_mmu"
      ],
      "caller_func": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980752,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581115655,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/memory.c:265",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:arch_tlb_finish_mmu"
      ],
      "caller_func": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115568,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256944,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:80",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/mmu_gather.c:arch_tlb_finish_mmu",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256944,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331872,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331872,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391280,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391280,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581589058,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:246",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
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
      "addr": 18446744071581588400,
      "name": "tlb_flush_mmu",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581635010,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:246",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
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
      "addr": 18446744071581634352,
      "name": "tlb_flush_mmu",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581656626,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:246",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
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
      "addr": 18446744071581655968,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581924818,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:246",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
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
      "addr": 18446744071581924160,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582331616,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:259",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
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
      "addr": 18446744071582330976,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582832032,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:296",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
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
      "addr": 18446744071582831360,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583047424,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:296",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
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
      "addr": 18446744071583046752,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583229264,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:297",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
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
      "addr": 18446744071583228624,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492797024,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492797024,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226611796,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:free_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226611276,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286167792,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:free_pgd_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286167792,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272764886,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272764534,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581360128,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360128,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581303840,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303840,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351328,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351328,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void tlb_flush_mmu(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415264,
      "name": "tlb_flush_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:188",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:tlb_remove_page",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:zap_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415264,
      "name": "tlb_flush_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
