# Function: <code>copy_pte_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580683738,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:888",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796870,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:924",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580861142,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:926",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580905962,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:992",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984032,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:1059",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984032,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581118768,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:1073",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118768,
      "name": "copy_pte_range.isra.93",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1964
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581197552,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:816",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197552,
      "name": "copy_pte_range.isra.84",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1972
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581270848,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270848,
      "name": "copy_pte_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1809
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581329648,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329648,
      "name": "copy_pte_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1809
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
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581528112,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:812",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528112,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
int copy_pte_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pmd_t * dst_pmd, pmd_t * src_pmd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570960,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:923",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570960,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1946
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
int copy_pte_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pmd_t * dst_pmd, pmd_t * src_pmd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592000,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:929",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pmd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592000,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1921
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
int copy_pte_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pmd_t * dst_pmd, pmd_t * src_pmd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858816,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:1003",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_pmd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858816,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2028
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
int copy_pte_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pmd_t * dst_pmd, pmd_t * src_pmd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254128,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:1010",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254128,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1474
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
int copy_pte_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pmd_t * dst_pmd, pmd_t * src_pmd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745552,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:967",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745552,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
int copy_pte_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pmd_t * dst_pmd, pmd_t * src_pmd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582962080,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:1001",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582962080,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int copy_pte_range(struct vm_area_struct * dst_vma, struct vm_area_struct * src_vma, pmd_t * dst_pmd, pmd_t * src_pmd, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583139696,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:1021",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583139696,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1133
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
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492737288,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492737288,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1628
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
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226567868,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226567868,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1504
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
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286086896,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286086896,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2676
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
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272735374,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581298496,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298496,
      "name": "copy_pte_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1809
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
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243520,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243520,
      "name": "copy_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581289696,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289696,
      "name": "copy_pte_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1809
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581353824,
      "name": "copy_pte_range",
      "external": false,
      "loc": "mm/memory.c:784",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353824,
      "name": "copy_pte_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1861
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct * dst_vma</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_area_struct * src_vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * dst_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * src_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, src_mm, dst_pmd, src_pmd, vma, addr, end</code> ➡️ <code>dst_vma, src_vma, dst_pmd, src_pmd, addr, end</code>
</li>
</ul>
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
int copy_pte_range(struct mm_struct * dst_mm, struct mm_struct * src_mm, pmd_t * dst_pmd, pmd_t * src_pmd, struct vm_area_struct * vma, long unsigned int addr, long unsigned int end)
```
</details>
</li>
</ul>
