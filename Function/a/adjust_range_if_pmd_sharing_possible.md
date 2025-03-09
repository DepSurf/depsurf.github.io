# Function: <code>adjust_range_if_pmd_sharing_possible</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376064,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4624",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376064,
      "name": "adjust_range_if_pmd_sharing_possible",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486960,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4729",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486960,
      "name": "adjust_range_if_pmd_sharing_possible",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551376,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4846",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551376,
      "name": "adjust_range_if_pmd_sharing_possible",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581767226,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:5334",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761760,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809824,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:5337",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809824,
      "name": "adjust_range_if_pmd_sharing_possible",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838304,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:5615",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838304,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129136,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:5952",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129136,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582575904,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:6678",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575904,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583094784,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:7024",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:zap_page_range_single",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094784,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583304624,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:7119",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:zap_page_range_single",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583304624,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583537566,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:7256",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__hugetlb_zap_begin"
      ],
      "caller_func": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542496,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492987576,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4846",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492987576,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": false,
      "loc": "include/linux/hugetlb.h:161",
      "file": "mm/rmap.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286424448,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4968",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286424448,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272890410,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4846",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272890410,
      "name": "adjust_range_if_pmd_sharing_possible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520112,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4846",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520112,
      "name": "adjust_range_if_pmd_sharing_possible",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462272,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4846",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462272,
      "name": "adjust_range_if_pmd_sharing_possible",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511424,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4846",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511424,
      "name": "adjust_range_if_pmd_sharing_possible",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
```

```json
{
  "name": "adjust_range_if_pmd_sharing_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576480,
      "name": "adjust_range_if_pmd_sharing_possible",
      "external": true,
      "loc": "mm/hugetlb.c:4846",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576480,
      "name": "adjust_range_if_pmd_sharing_possible",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct * vma, long unsigned int * start, long unsigned int * end)
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
