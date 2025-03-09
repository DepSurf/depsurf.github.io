# Function: <code>mm_find_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580723232,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:717",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:__page_check_address",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580723232,
      "name": "mm_find_pmd",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840496,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:685",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:__page_check_address",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840496,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580911040,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:684",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:__page_check_address",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911040,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580957280,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:708",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957280,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581058912,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:709",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058912,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197648,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:710",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197648,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280992,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:710",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280992,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581355616,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:710",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355616,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415152,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415152,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581616240,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:724",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581616240,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581663232,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:724",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581663232,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685280,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:728",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685280,
      "name": "mm_find_pmd",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:729",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592201573,
      "name": "mm_find_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581954720,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:773",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593978314,
      "name": "mm_find_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582369968,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:773",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/khugepaged.c:find_pmd_or_thp_or_none"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596034169,
      "name": "mm_find_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582871440,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:776",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/khugepaged.c:find_pmd_or_thp_or_none"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596556222,
      "name": "mm_find_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583088272,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:801",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/khugepaged.c:find_pmd_or_thp_or_none",
        "mm/userfaultfd.c:move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597460460,
      "name": "mm_find_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583270704,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492814992,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492814992,
      "name": "mm_find_pmd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226623904,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226623904,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286195872,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286195872,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272774958,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272774958,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384000,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384000,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326816,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326816,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375200,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375200,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
pmd_t * mm_find_pmd(struct mm_struct * mm, long unsigned int address)
```

```json
{
  "name": "mm_find_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439056,
      "name": "mm_find_pmd",
      "external": true,
      "loc": "mm/rmap.c:711",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439056,
      "name": "mm_find_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
