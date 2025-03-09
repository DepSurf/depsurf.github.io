# Function: <code>folio_mapcount</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int folio_mapcount(struct folio * folio)
```

```json
{
  "name": "folio_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582113536,
      "name": "folio_mapcount",
      "external": true,
      "loc": "mm/util.c:845",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:folio_referenced",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/huge_memory.c:can_split_folio",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:is_refcount_suitable",
        "mm/memfd.c:memfd_wait_for_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113536,
      "name": "folio_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
  "name": "folio_mapcount",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582873221,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:906",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:folio_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991509,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:906",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308330,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:906",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:can_split_folio"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "folio_mapcount",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582888462,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1151",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087504,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1151",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:folio_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201785,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1151",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583316225,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1151",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583527930,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1151",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:can_split_folio"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "folio_mapcount",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583060680,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1234",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269962,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1234",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:folio_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437328,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1234",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553929,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1234",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722362,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1234",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:can_split_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583737717,
      "name": "folio_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:1234",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:is_refcount_suitable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int folio_mapcount(struct folio * folio)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int folio_mapcount(struct folio * folio)
```
</details>
</li>
</ul>
