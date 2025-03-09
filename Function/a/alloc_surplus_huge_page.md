# Function: <code>alloc_surplus_huge_page</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281792,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1549",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281792,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581364080,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1549",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364080,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477936,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1591",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477936,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542224,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1671",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542224,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751904,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1916",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:gather_surplus_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751904,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800112,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1885",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:gather_surplus_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800112,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827520,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1832",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:gather_surplus_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827520,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, bool zero_ref)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:2060",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:gather_surplus_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113808,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071592211748,
      "name": "alloc_surplus_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, bool zero_ref)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:2172",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:gather_surplus_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556400,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071593990213,
      "name": "alloc_surplus_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076896,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:2382",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:gather_surplus_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076896,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    }
  ]
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492973992,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1671",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492973992,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286393376,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1671",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286393376,
      "name": "alloc_surplus_huge_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272880326,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1671",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272880326,
      "name": "alloc_surplus_huge_page.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510960,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1671",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510960,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581453152,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1671",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453152,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502272,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1671",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502272,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_surplus_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567216,
      "name": "alloc_surplus_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1671",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567216,
      "name": "alloc_surplus_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool zero_ref</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool zero_ref</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
struct page * alloc_surplus_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
