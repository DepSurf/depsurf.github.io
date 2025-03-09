# Function: <code>replace_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580833273,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:930",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page"
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
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580958898,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:918",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page"
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
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581032478,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:936",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
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
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581079571,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1094",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
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
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581190948,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1099",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
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
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581336578,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1122",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
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
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581420357,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1122",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581529616,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1137",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529616,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 950
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581594512,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594512,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809120,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809120,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581856736,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1120",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856736,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891840,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1118",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891840,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582186544,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1114",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186544,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 987
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582646256,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1132",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582646256,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166080,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1136",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166080,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1224
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583382160,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1179",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382160,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1106
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621824,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1370",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621824,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493034380,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226750544,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226750544,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286467424,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286467424,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
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
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272910460,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581563248,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563248,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504864,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504864,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 914
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581554560,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554560,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```

```json
{
  "name": "replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581619616,
      "name": "replace_page",
      "external": false,
      "loc": "mm/ksm.c:1119",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619616,
      "name": "replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 946
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
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int replace_page(struct vm_area_struct * vma, struct page * page, struct page * kpage, pte_t orig_pte)
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
