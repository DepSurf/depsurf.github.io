# Function: <code>alloc_fresh_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int alloc_fresh_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791152,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1351",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791152,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int alloc_fresh_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914608,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1378",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914608,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int alloc_fresh_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580985056,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1378",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985056,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int alloc_fresh_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581031024,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1396",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581031024,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int alloc_fresh_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140640,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1402",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140640,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279456,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1397",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279456,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 877
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361984,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1398",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361984,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473296,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1429",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473296,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581537312,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1506",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537312,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747328,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1751",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747328,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795616,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1699",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795616,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824048,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1654",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824048,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1845",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113488,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071592211693,
      "name": "alloc_fresh_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1957",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582553936,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071593989882,
      "name": "alloc_fresh_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492971136,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1506",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492971136,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286388080,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1506",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286388080,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1488
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272876904,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1506",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272876904,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506048,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1506",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506048,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448240,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1506",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448240,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581497360,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1506",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497360,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_fresh_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564336,
      "name": "alloc_fresh_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1506",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564336,
      "name": "alloc_fresh_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param added. </b>
<code>nodemask_t * nmask</code>
</li>
<li>
<b>Param removed. </b>
<code>nodemask_t * nodes_allowed</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct page *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>nodemask_t * node_alloc_noretry</code>
</li>
</ul>
</details>
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
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
struct page * alloc_fresh_huge_page(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask, nodemask_t * node_alloc_noretry)
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
