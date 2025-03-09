# Function: <code>pmd_huge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579315056,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:62",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "mm/gup.c:follow_page_mask",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315056,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317248,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:62",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "mm/gup.c:follow_page_mask",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317248,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579332528,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:62",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "mm/gup.c:follow_page_mask",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332528,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326416,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:65",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "mm/gup.c:__get_user_pages_fast",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326416,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579351568,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351568,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579363328,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pgd_range",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363328,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390848,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pud_range",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390848,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406208,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pud_range",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406208,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409392,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pud_range",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409392,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440336,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:66",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_pte_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440336,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438592,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:65",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:apply_to_pte_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438592,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441104,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:65",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pgd_range",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:apply_to_pte_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441104,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505488,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:65",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pgd_range",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:apply_to_pte_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505488,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587680,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:65",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pgd_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587680,
      "name": "pmd_huge",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698144,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:27",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/memory.c:apply_to_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698144,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712000,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:27",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712000,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746704,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:27",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746704,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490357052,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/arm64/mm/hugetlbpage.c:42",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/hugetlbpage.c:huge_pte_offset"
      ],
      "caller_func": [
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:stage2_wp_range",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:stage2_get_leaf_entry",
        "virt/kvm/arm/mmu.c:unmap_stage2_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490355288,
      "name": "pmd_huge",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pmd_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282776824,
      "name": "pmd_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable-64k.h:17",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286057424,
      "name": "pmd_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable-64k.h:17",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286075408,
      "name": "pmd_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable-64k.h:17",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286424788,
      "name": "pmd_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable-64k.h:17",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271361524,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/riscv/mm/hugetlbpage.c:11",
      "file": "arch/riscv/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271361524,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405232,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pud_range",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405232,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334672,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334672,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405152,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pud_range",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405152,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pmd_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_huge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414016,
      "name": "pmd_huge",
      "external": true,
      "loc": "arch/x86/mm/hugetlbpage.c:67",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "mm/gup.c:gup_pud_range",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:apply_to_page_range",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pte_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414016,
      "name": "pmd_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pmd_huge(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pmd_huge(pmd_t pmd)
```
</details>
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
