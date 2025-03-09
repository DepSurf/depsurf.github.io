# Function: <code>alloc_migrate_huge_page</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581288470,
      "name": "alloc_migrate_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1589",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
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
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581371382,
      "name": "alloc_migrate_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1589",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581482195,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1632",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481792,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581546611,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1712",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546208,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581756592,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1957",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756192,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581804574,
      "name": "alloc_migrate_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1926",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581831797,
      "name": "alloc_migrate_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1873",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582121301,
      "name": "alloc_migrate_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:2127",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582567048,
      "name": "alloc_migrate_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:2239",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583085704,
      "name": "alloc_migrate_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:2423",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492980896,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1712",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492980272,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286401648,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1712",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286400816,
      "name": "alloc_migrate_huge_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272886052,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1712",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272885800,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581515347,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1712",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514944,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581457539,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1712",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457136,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581506659,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1712",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506256,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_migrate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581571678,
      "name": "alloc_migrate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1712",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ],
      "caller_func": [
        "mm/gup.c:new_non_cma_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571264,
      "name": "alloc_migrate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
struct page * alloc_migrate_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
