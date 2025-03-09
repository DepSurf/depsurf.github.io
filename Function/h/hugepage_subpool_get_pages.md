# Function: <code>hugepage_subpool_get_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int hugepage_subpool_get_pages(struct hugepage_subpool * spool, long int delta)
```

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580785152,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:129",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785152,
      "name": "hugepage_subpool_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int hugepage_subpool_get_pages(struct hugepage_subpool * spool, long int delta)
```

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908528,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:129",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908528,
      "name": "hugepage_subpool_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int hugepage_subpool_get_pages(struct hugepage_subpool * spool, long int delta)
```

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976544,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:129",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976544,
      "name": "hugepage_subpool_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581039177,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:131",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027104,
      "name": "hugepage_subpool_get_pages.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581149090,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:132",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136560,
      "name": "hugepage_subpool_get_pages.part.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292528,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:131",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280336,
      "name": "hugepage_subpool_get_pages.part.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581375440,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:131",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581362864,
      "name": "hugepage_subpool_get_pages.part.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581486364,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:133",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473152,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581550780,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:134",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537168,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581760847,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:140",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746848,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581808821,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:157",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795152,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581837319,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:154",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823408,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582128042,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:156",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109792,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582574511,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:170",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548192,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583093278,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:170",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583064928,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583303270,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:170",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275584,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583540974,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:172",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583511872,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492986836,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:134",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492969536,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286423552,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:134",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286389568,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272889816,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:134",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272876732,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581519516,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:134",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505904,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581461676,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:134",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448096,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581510828,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:134",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497216,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "hugepage_subpool_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581575840,
      "name": "hugepage_subpool_get_pages",
      "external": false,
      "loc": "mm/hugetlb.c:134",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561664,
      "name": "hugepage_subpool_get_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
long int hugepage_subpool_get_pages(struct hugepage_subpool * spool, long int delta)
```
</details>
</li>
</ul>
