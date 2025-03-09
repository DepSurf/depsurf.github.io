# Function: <code>hugetlb_no_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580806794,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3521",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
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
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580930939,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3536",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
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
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580999242,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3650",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
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
int hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042528,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3636",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042528,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
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
int hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152912,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3657",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152912,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3686",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296272,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1486
    },
    {
      "addr": 18446744071581305126,
      "name": "hugetlb_no_page.cold.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3719",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379536,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
    },
    {
      "addr": 18446744071581388810,
      "name": "hugetlb_no_page.cold.81",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3790",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490528,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1855
    },
    {
      "addr": 18446744071581500515,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3907",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555008,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1855
    },
    {
      "addr": 18446744071581565018,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:4329",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765472,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1621
    },
    {
      "addr": 18446744071581775729,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:4319",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813648,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1601
    },
    {
      "addr": 18446744071591332551,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:4573",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841936,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
    },
    {
      "addr": 18446744071591275251,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:4878",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133232,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1372
    },
    {
      "addr": 18446744071592213968,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, pte_t old_pte, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:5496",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581600,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1623
    },
    {
      "addr": 18446744071593992531,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, pte_t old_pte, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:5748",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107936,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1820
    },
    {
      "addr": 18446744071596043494,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, pte_t old_pte, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:5847",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583317920,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1874
    },
    {
      "addr": 18446744071596565845,
      "name": "hugetlb_no_page.cold",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, pte_t old_pte, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:6115",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583555680,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1885
    },
    {
      "addr": 18446744071597471506,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492992024,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3907",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492992024,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1796
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286413392,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3907",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286413392,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2692
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272893408,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3907",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272893408,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1578
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3907",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523744,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1855
    },
    {
      "addr": 18446744071581533754,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3907",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465760,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1914
    },
    {
      "addr": 18446744071581475530,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3907",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515056,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1855
    },
    {
      "addr": 18446744071581525066,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```

```json
{
  "name": "hugetlb_no_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_no_page",
      "external": false,
      "loc": "mm/hugetlb.c:3907",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580064,
      "name": "hugetlb_no_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1842
    },
    {
      "addr": 18446744071581589979,
      "name": "hugetlb_no_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pte_t old_pte</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, mapping, idx, address, ptep, flags</code> ➡️ <code>mm, vma, mapping, idx, address, ptep, old_pte, flags</code>
</li>
</ul>
</details>
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
vm_fault_t hugetlb_no_page(struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address, pte_t * ptep, unsigned int flags)
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
