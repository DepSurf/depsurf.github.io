# Function: <code>khugepaged_scan_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580895624,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/huge_memory.c:2641",
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
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581056077,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1089",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581126547,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1091",
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
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581177644,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1092",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581303799,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1098",
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
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581453757,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1098",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
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
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581538594,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1097",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581646000,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1102",
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
      "addr": 18446744071581646000,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1405
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717696,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1115",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717696,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1405
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936608,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1197",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936608,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1632
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979152,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1224",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979152,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1653
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582007168,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1218",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582007168,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1619
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582309552,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1222",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582309552,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1619
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805776,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1197",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805776,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1973
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493165064,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1115",
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
      "addr": 18446603336493165064,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286652224,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1115",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286652224,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1792
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686432,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1115",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686432,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1405
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625488,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1115",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625488,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1395
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677744,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1115",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677744,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1405
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_pmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581744368,
      "name": "khugepaged_scan_pmd",
      "external": false,
      "loc": "mm/khugepaged.c:1115",
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
      "addr": 18446744071581744368,
      "name": "khugepaged_scan_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
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
int khugepaged_scan_pmd(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, struct page * * hpage)
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
