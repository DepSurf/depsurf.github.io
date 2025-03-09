# Function: <code>alloc_pool_huge_page</code>

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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281552,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1421",
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
      "addr": 18446744071581281552,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581364384,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1422",
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
      "addr": 18446744071581364384,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581474832,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1453",
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
      "addr": 18446744071581474832,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538944,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1531",
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
      "addr": 18446744071581538944,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749008,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1776",
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
      "addr": 18446744071581749008,
      "name": "alloc_pool_huge_page",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797136,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1724",
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
      "addr": 18446744071581797136,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824224,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1679",
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
      "addr": 18446744071581824224,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114112,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1884",
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
      "addr": 18446744071582114112,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556688,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1996",
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
      "addr": 18446744071582556688,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079440,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:2210",
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
      "addr": 18446744071583079440,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289984,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:2237",
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
      "addr": 18446744071583289984,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    }
  ]
}
```
</details>
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492971584,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1531",
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
      "addr": 18446603336492971584,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286390736,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1531",
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
      "addr": 13835058055286390736,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272880722,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1531",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272880722,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581507680,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1531",
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
      "addr": 18446744071581507680,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449872,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1531",
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
      "addr": 18446744071581449872,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498992,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1531",
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
      "addr": 18446744071581498992,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
```

```json
{
  "name": "alloc_pool_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581565616,
      "name": "alloc_pool_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1531",
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
      "addr": 18446744071581565616,
      "name": "alloc_pool_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
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
int alloc_pool_huge_page(struct hstate * h, nodemask_t * nodes_allowed, nodemask_t * node_alloc_noretry)
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
