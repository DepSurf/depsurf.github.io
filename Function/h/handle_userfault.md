# Function: <code>handle_userfault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int handle_userfault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314016,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:260",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314016,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
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
int handle_userfault(struct fault_env * fe, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480848,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:260",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480848,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1274
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
int handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561520,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:267",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561520,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1601
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
int handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581616880,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:336",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581616880,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1660
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
int handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761376,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:336",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761376,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1809
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
int handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930128,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:343",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930128,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1763
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582014544,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:342",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014544,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1763
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151120,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151120,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1775
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228400,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228400,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1775
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466432,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:381",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466432,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1398
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:368",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341094,
      "name": "handle_userfault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582523712,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:366",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591283795,
      "name": "handle_userfault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582552512,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1127
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:367",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592236730,
      "name": "handle_userfault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071582868672,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1101
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:376",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594016933,
      "name": "handle_userfault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583432192,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:392",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596056583,
      "name": "handle_userfault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584021632,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1003
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:415",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596580757,
      "name": "handle_userfault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071584246304,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1203
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:416",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_wp_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597484677,
      "name": "handle_userfault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584462752,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493797920,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493797920,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227308304,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227308304,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287411728,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287411728,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2368
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273384878,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273384878,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1118
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582197136,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197136,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1775
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134608,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134608,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1663
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187616,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187616,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1775
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
vm_fault_t handle_userfault(struct vm_fault * vmf, long unsigned int reason)
```

```json
{
  "name": "handle_userfault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263744,
      "name": "handle_userfault",
      "external": true,
      "loc": "fs/userfaultfd.c:352",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263744,
      "name": "handle_userfault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1757
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fault_env * fe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, address, flags, reason</code> ➡️ <code>fe, reason</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env * fe</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
