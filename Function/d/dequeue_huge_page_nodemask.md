# Function: <code>dequeue_huge_page_nodemask</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025296,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:890",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025296,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134800,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:891",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134800,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276048,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:883",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276048,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358992,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:883",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358992,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470832,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:893",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470832,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535488,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:894",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535488,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742512,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:1059",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742512,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791536,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:1093",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791536,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581820688,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:1103",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820688,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106784,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:1107",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106784,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 903
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545440,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:1155",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545440,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1078
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583062608,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:1315",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583062608,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492963840,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:894",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492963840,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286382096,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:894",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286382096,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272875556,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:894",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272875556,
      "name": "dequeue_huge_page_nodemask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504224,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:894",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504224,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446528,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:894",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446528,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581495536,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:894",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495536,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581562992,
      "name": "dequeue_huge_page_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:894",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562992,
      "name": "dequeue_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
struct page * dequeue_huge_page_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
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
