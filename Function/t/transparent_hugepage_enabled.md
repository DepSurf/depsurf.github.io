# Function: <code>transparent_hugepage_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580899533,
      "name": "transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:94",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158880,
      "name": "transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:94",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581001282,
      "name": "transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:95",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283292,
      "name": "transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:95",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581138581,
      "name": "transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:96",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432099,
      "name": "transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:96",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503104,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503104,
      "name": "transparent_hugepage_enabled",
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612784,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612784,
      "name": "transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581683696,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581683696,
      "name": "transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902112,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902112,
      "name": "transparent_hugepage_enabled",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948288,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948288,
      "name": "transparent_hugepage_enabled",
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493130488,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493130488,
      "name": "transparent_hugepage_enabled",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:300",
      "file": "fs/proc/task_mmu.c",
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286609168,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286609168,
      "name": "transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:300",
      "file": "fs/proc/task_mmu.c",
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652432,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652432,
      "name": "transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592656,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592656,
      "name": "transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643744,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643744,
      "name": "transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "transparent_hugepage_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710128,
      "name": "transparent_hugepage_enabled",
      "external": true,
      "loc": "mm/huge_memory.c:65",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710128,
      "name": "transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
```
</details>
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
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
bool transparent_hugepage_enabled(struct vm_area_struct * vma)
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
