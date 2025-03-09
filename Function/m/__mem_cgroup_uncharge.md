# Function: <code>__mem_cgroup_uncharge</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "__mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582365392,
      "name": "__mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6928",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page_alloc.c:free_compound_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memremap.c:free_devmap_managed_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365392,
      "name": "__mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __mem_cgroup_uncharge(struct folio * folio)
```

```json
{
  "name": "__mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582863040,
      "name": "__mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6911",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/swap.c:__put_page",
        "mm/page_alloc.c:free_compound_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memremap.c:free_zone_device_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582863040,
      "name": "__mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __mem_cgroup_uncharge(struct folio * folio)
```

```json
{
  "name": "__mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583410448,
      "name": "__mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:7100",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/swap.c:__folio_put",
        "mm/page_alloc.c:free_compound_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memremap.c:free_zone_device_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410448,
      "name": "__mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __mem_cgroup_uncharge(struct folio * folio)
```

```json
{
  "name": "__mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583630704,
      "name": "__mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:7168",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/swap.c:__folio_put",
        "mm/page_alloc.c:free_compound_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memremap.c:free_zone_device_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630704,
      "name": "__mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __mem_cgroup_uncharge(struct folio * folio)
```

```json
{
  "name": "__mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583825488,
      "name": "__mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:7495",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/swap.c:__folio_put",
        "mm/page_alloc.c:destroy_large_folio",
        "mm/hugetlb.c:free_huge_folio",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memremap.c:free_zone_device_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825488,
      "name": "__mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void __mem_cgroup_uncharge(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
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
