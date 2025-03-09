# Function: <code>lru_gen_add_folio</code>

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
bool lru_gen_add_folio(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "lru_gen_add_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:220",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn"
      ]
    },
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:220",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:move_folios_to_lru"
      ]
    },
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:220",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439712,
      "name": "lru_gen_add_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
    },
    {
      "addr": 18446744071596025605,
      "name": "lru_gen_add_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582493312,
      "name": "lru_gen_add_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
    },
    {
      "addr": 18446744071596026219,
      "name": "lru_gen_add_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582786368,
      "name": "lru_gen_add_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
    },
    {
      "addr": 18446744071596032646,
      "name": "lru_gen_add_folio.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
bool lru_gen_add_folio(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "lru_gen_add_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:220",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn"
      ]
    },
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:220",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:move_folios_to_lru"
      ]
    },
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:220",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645088,
      "name": "lru_gen_add_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
    },
    {
      "addr": 18446744071596547756,
      "name": "lru_gen_add_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582682512,
      "name": "lru_gen_add_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
    },
    {
      "addr": 18446744071596548138,
      "name": "lru_gen_add_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583001744,
      "name": "lru_gen_add_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
    },
    {
      "addr": 18446744071596554593,
      "name": "lru_gen_add_folio.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
bool lru_gen_add_folio(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "lru_gen_add_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:221",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn"
      ]
    },
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:221",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:move_folios_to_lru"
      ]
    },
    {
      "addr": 0,
      "name": "lru_gen_add_folio",
      "external": false,
      "loc": "include/linux/mm_inline.h:221",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816192,
      "name": "lru_gen_add_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
    },
    {
      "addr": 18446744071597451464,
      "name": "lru_gen_add_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582853264,
      "name": "lru_gen_add_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
    },
    {
      "addr": 18446744071597451838,
      "name": "lru_gen_add_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583182448,
      "name": "lru_gen_add_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
    },
    {
      "addr": 18446744071597458660,
      "name": "lru_gen_add_folio.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
bool lru_gen_add_folio(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
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
