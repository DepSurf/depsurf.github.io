# Function: <code>alloc_huge_page_nodemask</code>

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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035472,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1645",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035472,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145216,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1651",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145216,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288352,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1651",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288352,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371264,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1651",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371264,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581482064,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1694",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482064,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546480,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1774",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546480,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756464,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:2019",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756464,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804480,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1968",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/migrate.c:alloc_migration_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804480,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831696,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1915",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/migrate.c:alloc_migration_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831696,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582121200,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:2179",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/migrate.c:alloc_migration_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121200,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566960,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:2291",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/migrate.c:alloc_migration_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566960,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583085616,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:2477",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/migrate.c:alloc_migration_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583085616,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492980744,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1774",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492980744,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_huge_page_nodemask",
      "external": false,
      "loc": "include/linux/hugetlb.h:607",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286401408,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1774",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286401408,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272886110,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1774",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272886110,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515216,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1774",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515216,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457408,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1774",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457408,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506528,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1774",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506528,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
```

```json
{
  "name": "alloc_huge_page_nodemask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571552,
      "name": "alloc_huge_page_nodemask",
      "external": true,
      "loc": "mm/hugetlb.c:1774",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571552,
      "name": "alloc_huge_page_nodemask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask, gfp_t gfp_mask)
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
struct page * alloc_huge_page_nodemask(struct hstate * h, int preferred_nid, nodemask_t * nmask)
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
