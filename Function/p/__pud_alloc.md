# Function: <code>__pud_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct * mm, pgd_t * pgd, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674496,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:3475",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674496,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int __pud_alloc(struct mm_struct * mm, pgd_t * pgd, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788704,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:3670",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788704,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int __pud_alloc(struct mm_struct * mm, pgd_t * pgd, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853072,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:3725",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853072,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898256,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:3988",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898256,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581000336,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4164",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000336,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581133968,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4209",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133968,
      "name": "__pud_alloc",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210400,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:3999",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210400,
      "name": "__pud_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286560,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4048",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286560,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345280,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4073",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345280,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581541632,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4454",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_p4d_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/vmalloc.c:vmap_p4d_range",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541632,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581584816,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4677",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_p4d_range",
        "mm/vmalloc.c:vmap_p4d_range",
        "mm/ioremap.c:ioremap_page_range",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584816,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581607056,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4704",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_p4d_range",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607056,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874176,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4850",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874176,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272416,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:5193",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/mprotect.c:change_protection_range",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272416,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582764480,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:5273",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/mprotect.c:change_protection_range",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764480,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980848,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:5465",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980848,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156128,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:5691",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/userfaultfd.c:mm_alloc_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156128,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int __pud_alloc(struct mm_struct * mm, pgd_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492750864,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4073",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/hugetlbpage.c:huge_pte_alloc",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492750864,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
  "name": "__pud_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "arch/arm/mm/pgd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "lib/ioremap.c",
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
int __pud_alloc(struct mm_struct * mm, pgd_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286110048,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4073",
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
      "addr": 13835058055286110048,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
  "name": "__pud_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pud_alloc",
      "external": false,
      "loc": "include/linux/mm.h:1781",
      "file": "lib/ioremap.c",
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314128,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4073",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314128,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257760,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4073",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257760,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581305328,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4073",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305328,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "__pud_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369328,
      "name": "__pud_alloc",
      "external": true,
      "loc": "mm/memory.c:4073",
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
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/userfaultfd.c:mm_alloc_pmd",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369328,
      "name": "__pud_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
<code>p4d_t * p4d</code>
</li>
<li>
<b>Param removed. </b>
<code>pgd_t * pgd</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t * p4d</code> ➡️ <code>pgd_t * p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t * p4d</code> ➡️ <code>pgd_t * p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __pud_alloc(struct mm_struct * mm, p4d_t * p4d, long unsigned int address)
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
