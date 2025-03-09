# Function: <code>folio_isolate_lru</code>

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
int folio_isolate_lru(struct folio * folio)
```

```json
{
  "name": "folio_isolate_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070800,
      "name": "folio_isolate_lru",
      "external": true,
      "loc": "mm/vmscan.c:2193",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:isolate_lru_page",
        "mm/gup.c:check_and_migrate_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070800,
      "name": "folio_isolate_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int folio_isolate_lru(struct folio * folio)
```

```json
{
  "name": "folio_isolate_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542640,
      "name": "folio_isolate_lru",
      "external": true,
      "loc": "mm/vmscan.c:2337",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:isolate_lru_page",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542640,
      "name": "folio_isolate_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
bool folio_isolate_lru(struct folio * folio)
```

```json
{
  "name": "folio_isolate_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582740416,
      "name": "folio_isolate_lru",
      "external": true,
      "loc": "mm/vmscan.c:2421",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:isolate_lru_page",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_folio_add",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582740416,
      "name": "folio_isolate_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
bool folio_isolate_lru(struct folio * folio)
```

```json
{
  "name": "folio_isolate_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582908000,
      "name": "folio_isolate_lru",
      "external": true,
      "loc": "mm/vmscan.c:1721",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:isolate_lru_page",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_folio_add",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582908000,
      "name": "folio_isolate_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int folio_isolate_lru(struct folio * folio)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
