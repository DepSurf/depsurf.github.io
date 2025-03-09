# Function: <code>__split_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581031808,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1636",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_mask",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581031808,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2427
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107104,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1764",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_mask",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107104,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2335
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157328,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2086",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157328,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279952,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2224",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279952,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2845
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428448,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2216",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428448,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2990
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514272,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2238",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514272,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623888,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2295",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623888,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694752,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2300",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694752,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912304,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2185",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912304,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1244
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581957952,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2200",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957952,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1192
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581983984,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2217",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mremap.c:move_page_tables",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983984,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285968,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2145",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mremap.c:move_page_tables",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285968,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1097
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct folio * folio)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582770032,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2200",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mremap.c:move_page_tables",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582770032,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct folio * folio)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583304656,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2281",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mremap.c:move_page_tables",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583304656,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct folio * folio)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583523968,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2274",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mremap.c:move_page_tables",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583523968,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct folio * folio)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718672,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2618",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mremap.c:move_page_tables",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/userfaultfd.c:move_pages",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718672,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493138968,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2300",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493138968,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_huge_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:336",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__split_huge_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:336",
      "file": "mm/mprotect.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286623376,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2300",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry",
        "arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286623376,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__split_huge_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:336",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__split_huge_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:336",
      "file": "mm/mprotect.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581663488,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2300",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581663488,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581603264,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2300",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603264,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654800,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2300",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654800,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```

```json
{
  "name": "__split_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721200,
      "name": "__split_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:2300",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721200,
      "name": "__split_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
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
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __split_huge_pmd(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int address, bool freeze, struct page * page)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
