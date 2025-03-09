# Function: <code>collapse_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580896617,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2505",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581047280,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:924",
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
      "addr": 18446744071581047280,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581126547,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:926",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171344,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:927",
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
      "addr": 18446744071581171344,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581303799,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:933",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449664,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:933",
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
      "addr": 18446744071581449664,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3724
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581533216,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:934",
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
      "addr": 18446744071581533216,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3847
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581644128,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:934",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644128,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1857
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715808,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:946",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715808,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1878
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced, int unmapped)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934800,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:1031",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934800,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1802
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced, int unmapped)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977008,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:1058",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977008,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2132
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced, int unmapped)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005024,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:1055",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005024,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2140
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced, int unmapped)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582307456,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:1059",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307456,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2092
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced, int unmapped)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582803408,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:1034",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803408,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2353
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
int collapse_huge_page(struct mm_struct * mm, long unsigned int address, int referenced, int unmapped, struct collapse_control * cc)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583337024,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:973",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337024,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2181
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
int collapse_huge_page(struct mm_struct * mm, long unsigned int address, int referenced, int unmapped, struct collapse_control * cc)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583556240,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:1086",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583556240,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2098
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
int collapse_huge_page(struct mm_struct * mm, long unsigned int address, int referenced, int unmapped, struct collapse_control * cc)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583756048,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:1083",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756048,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2204
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493162816,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:946",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493162816,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2244
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286650016,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:946",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286650016,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2196
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684544,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:946",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684544,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1878
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623152,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:946",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623152,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2333
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675856,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:946",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675856,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1878
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```

```json
{
  "name": "collapse_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742496,
      "name": "collapse_huge_page",
      "external": false,
      "loc": "mm/khugepaged.c:946",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742496,
      "name": "collapse_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1863
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int unmapped</code>
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
<b>Param removed. </b>
<code>struct page * * hpage</code>
</li>
<li>
<b>Param removed. </b>
<code>int node</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, address, hpage, node, referenced, unmapped</code> ➡️ <code>mm, address, referenced, unmapped, cc</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
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
void collapse_huge_page(struct mm_struct * mm, long unsigned int address, struct page * * hpage, int node, int referenced)
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
