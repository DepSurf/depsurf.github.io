# Function: <code>__collapse_huge_page_isolate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580897637,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/huge_memory.c:2197",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581049044,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:497",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581131899,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:499",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581172354,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:500",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581306155,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:501",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
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
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581450565,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:501",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581534152,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:520",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638432,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:520",
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
      "addr": 18446744071581638432,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709456,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:532",
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
      "addr": 18446744071581709456,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte, struct list_head * compound_pagelist)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927280,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:584",
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
      "addr": 18446744071581927280,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1392
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte, struct list_head * compound_pagelist)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974256,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:599",
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
      "addr": 18446744071581974256,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1261
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte, struct list_head * compound_pagelist)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002720,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:597",
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
      "addr": 18446744071582002720,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1599
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte, struct list_head * compound_pagelist)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582305168,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:601",
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
      "addr": 18446744071582305168,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1593
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte, struct list_head * compound_pagelist)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582794384,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:592",
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
      "addr": 18446744071582794384,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1911
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte, struct collapse_control * cc, struct list_head * compound_pagelist)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:533",
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
      "addr": 18446744071583334864,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2134
    },
    {
      "addr": 18446744071596047695,
      "name": "__collapse_huge_page_isolate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte, struct collapse_control * cc, struct list_head * compound_pagelist)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:545",
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
      "addr": 18446744071583554448,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1771
    },
    {
      "addr": 18446744071596570230,
      "name": "__collapse_huge_page_isolate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte, struct collapse_control * cc, struct list_head * compound_pagelist)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:535",
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
      "addr": 18446744071583747680,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
    },
    {
      "addr": 18446744071597474610,
      "name": "__collapse_huge_page_isolate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493156352,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:532",
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
      "addr": 18446603336493156352,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1220
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286646576,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:532",
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
      "addr": 13835058055286646576,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1888
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678192,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:532",
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
      "addr": 18446744071581678192,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581616400,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:532",
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
      "addr": 18446744071581616400,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669504,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:532",
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
      "addr": 18446744071581669504,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```

```json
{
  "name": "__collapse_huge_page_isolate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581735968,
      "name": "__collapse_huge_page_isolate",
      "external": false,
      "loc": "mm/khugepaged.c:532",
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
      "addr": 18446744071581735968,
      "name": "__collapse_huge_page_isolate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1420
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head * compound_pagelist</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct collapse_control * cc</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, address, pte, compound_pagelist</code> ➡️ <code>vma, address, pte, cc, compound_pagelist</code>
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
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
int __collapse_huge_page_isolate(struct vm_area_struct * vma, long unsigned int address, pte_t * pte)
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
