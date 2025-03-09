# Function: <code>ptep_set_access_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307856,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:409",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307856,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307664,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:413",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307664,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322896,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:413",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322896,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320160,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:423",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320160,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343248,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:425",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343248,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579354464,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:430",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354464,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579381584,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:496",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381584,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397040,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:483",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397040,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400352,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:479",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400352,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409584,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:486",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409584,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410224,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:486",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410224,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413392,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:486",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:wp_page_reuse",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413392,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476272,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:486",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476272,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554320,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:486",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554320,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660992,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:490",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660992,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675152,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:490",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675152,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709280,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:502",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709280,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490340880,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/arm64/mm/fault.c:197",
      "file": "arch/arm64/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490340880,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226621060,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "mm/pgtable-generic.c:55",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226621060,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282720432,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/powerpc/mm/pgtable.c:208",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282720432,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
  "name": "ptep_set_access_flags",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272734580,
      "name": "ptep_set_access_flags",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:349",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272897946,
      "name": "ptep_set_access_flags",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:349",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396256,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:479",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396256,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579325824,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:479",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325824,
      "name": "ptep_set_access_flags",
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396176,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:479",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396176,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
```

```json
{
  "name": "ptep_set_access_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404672,
      "name": "ptep_set_access_flags",
      "external": true,
      "loc": "arch/x86/mm/pgtable.c:479",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:insert_pfn",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404672,
      "name": "ptep_set_access_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ptep_set_access_flags(struct vm_area_struct * vma, long unsigned int address, pte_t * ptep, pte_t entry, int dirty)
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
