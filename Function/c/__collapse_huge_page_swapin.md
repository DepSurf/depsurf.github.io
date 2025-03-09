# Function: <code>__collapse_huge_page_swapin</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581047523,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:871",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581122400,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:873",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122400,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170320,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:872",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170320,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298208,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:878",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298208,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1139
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581445616,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:878",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581445616,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581529088,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:878",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529088,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581639824,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:878",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581639824,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710848,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:890",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710848,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928672,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:975",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928672,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 947
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975520,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:1002",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975520,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int haddr, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582001376,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:1000",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001376,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int haddr, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582304480,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:1004",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582304480,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int haddr, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802640,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:979",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802640,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
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
int __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int haddr, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583330000,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:905",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330000,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
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
int __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int haddr, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583549008,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:992",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549008,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int haddr, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583743280,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:986",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743280,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493157576,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:890",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493157576,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286648464,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:890",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286648464,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679584,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:890",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679584,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581618288,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:890",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581618288,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670896,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:890",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670896,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```

```json
{
  "name": "__collapse_huge_page_swapin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581737392,
      "name": "__collapse_huge_page_swapin",
      "external": false,
      "loc": "mm/khugepaged.c:890",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581737392,
      "name": "__collapse_huge_page_swapin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
```
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int haddr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
</ul>
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
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
bool __collapse_huge_page_swapin(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, int referenced)
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
