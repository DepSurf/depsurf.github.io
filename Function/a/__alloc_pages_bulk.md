# Function: <code>__alloc_pages_bulk</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int __alloc_pages_bulk(gfp_t gfp, int preferred_nid, nodemask_t * nodemask, int nr_pages, struct list_head * page_list, struct page * * page_array)
```

```json
{
  "name": "__alloc_pages_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581746336,
      "name": "__alloc_pages_bulk",
      "external": true,
      "loc": "mm/page_alloc.c:5023",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746336,
      "name": "__alloc_pages_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1504
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
long unsigned int __alloc_pages_bulk(gfp_t gfp, int preferred_nid, nodemask_t * nodemask, int nr_pages, struct list_head * page_list, struct page * * page_array)
```

```json
{
  "name": "__alloc_pages_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024560,
      "name": "__alloc_pages_bulk",
      "external": true,
      "loc": "mm/page_alloc.c:5199",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024560,
      "name": "__alloc_pages_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1807
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
long unsigned int __alloc_pages_bulk(gfp_t gfp, int preferred_nid, nodemask_t * nodemask, int nr_pages, struct list_head * page_list, struct page * * page_array)
```

```json
{
  "name": "__alloc_pages_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451392,
      "name": "__alloc_pages_bulk",
      "external": true,
      "loc": "mm/page_alloc.c:5244",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_area_alloc_pages",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451392,
      "name": "__alloc_pages_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2023
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
long unsigned int __alloc_pages_bulk(gfp_t gfp, int preferred_nid, nodemask_t * nodemask, int nr_pages, struct list_head * page_list, struct page * * page_array)
```

```json
{
  "name": "__alloc_pages_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960448,
      "name": "__alloc_pages_bulk",
      "external": true,
      "loc": "mm/page_alloc.c:5361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960448,
      "name": "__alloc_pages_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2081
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
long unsigned int __alloc_pages_bulk(gfp_t gfp, int preferred_nid, nodemask_t * nodemask, int nr_pages, struct list_head * page_list, struct page * * page_array)
```

```json
{
  "name": "__alloc_pages_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583177392,
      "name": "__alloc_pages_bulk",
      "external": true,
      "loc": "mm/page_alloc.c:4289",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "fs/splice.c:copy_splice_read",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177392,
      "name": "__alloc_pages_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1876
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
long unsigned int __alloc_pages_bulk(gfp_t gfp, int preferred_nid, nodemask_t * nodemask, int nr_pages, struct list_head * page_list, struct page * * page_array)
```

```json
{
  "name": "__alloc_pages_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361248,
      "name": "__alloc_pages_bulk",
      "external": true,
      "loc": "mm/page_alloc.c:4381",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "fs/splice.c:copy_splice_read",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361248,
      "name": "__alloc_pages_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1878
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
long unsigned int __alloc_pages_bulk(gfp_t gfp, int preferred_nid, nodemask_t * nodemask, int nr_pages, struct list_head * page_list, struct page * * page_array)
```
</details>
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
