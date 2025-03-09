# Function: <code>folio_putback_lru</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void folio_putback_lru(struct folio * folio)
```

```json
{
  "name": "folio_putback_lru",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582051632,
      "name": "folio_putback_lru",
      "external": true,
      "loc": "mm/vmscan.c:1359",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_page_list"
      ],
      "caller_func": [
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:putback_lru_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069840,
      "name": "folio_putback_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void folio_putback_lru(struct folio * folio)
```

```json
{
  "name": "folio_putback_lru",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582519510,
      "name": "folio_putback_lru",
      "external": true,
      "loc": "mm/vmscan.c:1458",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru"
      ],
      "caller_func": [
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:putback_lru_page",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541968,
      "name": "folio_putback_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void folio_putback_lru(struct folio * folio)
```

```json
{
  "name": "folio_putback_lru",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582721167,
      "name": "folio_putback_lru",
      "external": true,
      "loc": "mm/vmscan.c:1511",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru"
      ],
      "caller_func": [
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:putback_lru_page",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:release_pte_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582739744,
      "name": "folio_putback_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void folio_putback_lru(struct folio * folio)
```

```json
{
  "name": "folio_putback_lru",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582890560,
      "name": "folio_putback_lru",
      "external": true,
      "loc": "mm/vmscan.c:810",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru"
      ],
      "caller_func": [
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:putback_lru_page",
        "mm/folio-compat.c:putback_lru_page",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:release_pte_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907360,
      "name": "folio_putback_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void folio_putback_lru(struct folio * folio)
```
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
