# Function: <code>hugetlb_basepage_index</code>

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
long unsigned int hugetlb_basepage_index(struct page * page)
```

```json
{
  "name": "hugetlb_basepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830912,
      "name": "hugetlb_basepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:1589",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830912,
      "name": "hugetlb_basepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
long unsigned int hugetlb_basepage_index(struct page * page)
```

```json
{
  "name": "hugetlb_basepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_basepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:1780",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592212186,
      "name": "hugetlb_basepage_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582120192,
      "name": "hugetlb_basepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
long unsigned int hugetlb_basepage_index(struct page * page)
```

```json
{
  "name": "hugetlb_basepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_basepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:1892",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:vma_address",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/rmap.c:page_address_in_vma",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593990764,
      "name": "hugetlb_basepage_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582565232,
      "name": "hugetlb_basepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int hugetlb_basepage_index(struct page * page)
```

```json
{
  "name": "hugetlb_basepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_basepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:2088",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/rmap.c:page_address_in_vma",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596041541,
      "name": "hugetlb_basepage_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583084096,
      "name": "hugetlb_basepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int hugetlb_basepage_index(struct page * page)
```

```json
{
  "name": "hugetlb_basepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hugetlb_basepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:2115",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:filemap_cachestat",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:vma_address",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/rmap.c:vma_address",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596563742,
      "name": "hugetlb_basepage_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583294704,
      "name": "hugetlb_basepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
long unsigned int hugetlb_basepage_index(struct page * page)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
long unsigned int hugetlb_basepage_index(struct page * page)
```
</details>
</li>
</ul>
