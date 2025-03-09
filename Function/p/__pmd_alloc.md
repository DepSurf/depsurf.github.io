# Function: <code>__pmd_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674720,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:3498",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:__get_locked_pte",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674720,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788960,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:3693",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788960,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853328,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:3748",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853328,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898512,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4018",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898512,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581000608,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4196",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000608,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134240,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4241",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134240,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210672,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4031",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210672,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286832,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4080",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286832,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345552,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4105",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345552,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581541904,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4478",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_p4d_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/vmalloc.c:vmap_p4d_range",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541904,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581585088,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4701",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_p4d_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vmap_p4d_range",
        "mm/ioremap.c:ioremap_page_range",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581585088,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581607328,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4728",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_pmd_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607328,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874448,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4874",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_pmd_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874448,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272704,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:5216",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272704,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582764784,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:5296",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764784,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981168,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:5488",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981168,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156512,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:5714",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156512,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492751240,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4105",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/hugetlbpage.c:huge_pte_alloc",
        "arch/arm64/mm/hugetlbpage.c:huge_pte_alloc",
        "arch/arm64/mm/hugetlbpage.c:huge_pte_alloc",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492751240,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286110432,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4105",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page",
        "arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vmap_page_range_noflush",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286110432,
      "name": "__pmd_alloc",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272734024,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4105",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272734024,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314400,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4105",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314400,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257968,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4105",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257968,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581305600,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4105",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305600,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
```

```json
{
  "name": "__pmd_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369600,
      "name": "__pmd_alloc",
      "external": true,
      "loc": "mm/memory.c:4105",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_late_init",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369600,
      "name": "__pmd_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int __pmd_alloc(struct mm_struct * mm, pud_t * pud, long unsigned int address)
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
