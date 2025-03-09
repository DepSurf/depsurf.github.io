# Function: <code>lru_gen_del_folio</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool lru_gen_del_folio(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "lru_gen_del_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582438064,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:266",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release"
      ]
    },
    {
      "addr": 18446744071582498622,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:266",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable"
      ],
      "caller_func": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:isolate_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:folio_isolate_lru"
      ]
    },
    {
      "addr": 18446744071582667936,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:266",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    },
    {
      "addr": 18446744071582785440,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:266",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438064,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071582488624,
      "name": "lru_gen_del_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
    },
    {
      "addr": 18446744071582667936,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071582785440,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool lru_gen_del_folio(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "lru_gen_del_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582643440,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:266",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release"
      ]
    },
    {
      "addr": 18446744071582692021,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:266",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_change_state"
      ],
      "caller_func": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:folio_isolate_lru"
      ]
    },
    {
      "addr": 18446744071582878448,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:266",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    },
    {
      "addr": 18446744071583000816,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:266",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643440,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071582689648,
      "name": "lru_gen_del_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
    },
    {
      "addr": 18446744071582878448,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071583000816,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
bool lru_gen_del_folio(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "lru_gen_del_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582814544,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:272",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__page_cache_release"
      ]
    },
    {
      "addr": 18446744071582862166,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:272",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_change_state"
      ],
      "caller_func": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:folio_isolate_lru"
      ]
    },
    {
      "addr": 18446744071583049840,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:272",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    },
    {
      "addr": 18446744071583181520,
      "name": "lru_gen_del_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:272",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814544,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
    },
    {
      "addr": 18446744071582859792,
      "name": "lru_gen_del_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
    },
    {
      "addr": 18446744071583049840,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
    },
    {
      "addr": 18446744071583181520,
      "name": "lru_gen_del_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool lru_gen_del_folio(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
