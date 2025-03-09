# Function: <code>lru_gen_update_size</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void lru_gen_update_size(struct lruvec * lruvec, struct folio * folio, int old_gen, int new_gen)
```

```json
{
  "name": "lru_gen_update_size",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582439873,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:174",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_gen_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582498740,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:174",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:lru_gen_add_folio"
      ],
      "caller_func": [
        "mm/vmscan.c:lru_gen_look_around"
      ]
    },
    {
      "addr": 18446744071582668084,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:174",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582785588,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:174",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475344,
      "name": "lru_gen_update_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1751
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lru_gen_update_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582645253,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:174",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_gen_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582692139,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:174",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:lru_gen_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878596,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:174",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583000964,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:174",
      "file": "mm/mlock.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lru_gen_update_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582816361,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:175",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_gen_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862284,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:175",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:lru_gen_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583049988,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:175",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583181668,
      "name": "lru_gen_update_size",
      "external": false,
      "loc": "include/linux/mm_inline.h:175",
      "file": "mm/mlock.c",
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
void lru_gen_update_size(struct lruvec * lruvec, struct folio * folio, int old_gen, int new_gen)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void lru_gen_update_size(struct lruvec * lruvec, struct folio * folio, int old_gen, int new_gen)
```
</details>
</li>
</ul>
