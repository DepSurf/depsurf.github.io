# Function: <code>__transparent_hugepage_enabled</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581211531,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:100",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581515584,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:100",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581287662,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625106,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581346382,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695970,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581550482,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:133",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902228,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:133",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581593618,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948404,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:124",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool __transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581614198,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:147",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071581973828,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:147",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:transparent_hugepage_active"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582208,
      "name": "__transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool __transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581881250,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:147",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071582276436,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:147",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:transparent_hugepage_active"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847296,
      "name": "__transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool __transparent_hugepage_enabled(struct vm_area_struct * vma)
```

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582283419,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071582760125,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:transparent_hugepage_active"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239488,
      "name": "__transparent_hugepage_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492751976,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493139716,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:295",
      "file": "mm/memory.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286111392,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286625212,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:295",
      "file": "mm/memory.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581315230,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664706,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581258973,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604130,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581306430,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656018,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__transparent_hugepage_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581370430,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722415,
      "name": "__transparent_hugepage_enabled",
      "external": false,
      "loc": "include/linux/huge_mm.h:98",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:transparent_hugepage_enabled",
        "mm/huge_memory.c:transparent_hugepage_enabled"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool __transparent_hugepage_enabled(struct vm_area_struct * vma)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool __transparent_hugepage_enabled(struct vm_area_struct * vma)
```
</details>
</li>
</ul>
