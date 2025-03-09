# Function: <code>huge_pte_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800640,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:4305",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:__page_check_address",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800640,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924272,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:4327",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924272,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992624,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:4440",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992624,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040112,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:4603",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040112,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150096,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:4674",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150096,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293568,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:4703",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293568,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376592,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:4792",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376592,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487488,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:4897",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487488,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551904,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5014",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551904,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581762320,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5501",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:walk_hugetlb_range",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762320,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581810400,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5513",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:walk_hugetlb_range",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581810400,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838832,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5793",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:__walk_page_range",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838832,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:6130",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:__walk_page_range",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592213423,
      "name": "huge_pte_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582129680,
      "name": "huge_pte_offset",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:6857",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:__walk_page_range",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593991980,
      "name": "huge_pte_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582576688,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:7196",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:__walk_page_range",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596042473,
      "name": "huge_pte_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583095584,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:7295",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:__walk_page_range",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596564734,
      "name": "huge_pte_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583305424,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:7432",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:__walk_page_range",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597470301,
      "name": "huge_pte_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583543296,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490356744,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "arch/arm64/mm/hugetlbpage.c:258",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490356744,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282840608,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "arch/powerpc/mm/hugetlbpage.c:35",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282840608,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272890788,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5014",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272890788,
      "name": "huge_pte_offset",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520640,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5014",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520640,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462752,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5014",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462752,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511952,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5014",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511952,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```

```json
{
  "name": "huge_pte_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577008,
      "name": "huge_pte_offset",
      "external": true,
      "loc": "mm/hugetlb.c:5014",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577008,
      "name": "huge_pte_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int sz</code>
</li>
</ul>
</details>
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
pte_t * huge_pte_offset(struct mm_struct * mm, long unsigned int addr, long unsigned int sz)
```
</details>
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
