# Function: <code>folio_batch_move_lru</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void folio_batch_move_lru(struct folio_batch * fbatch, move_fn_t move_fn)
```

```json
{
  "name": "folio_batch_move_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448032,
      "name": "folio_batch_move_lru",
      "external": false,
      "loc": "mm/swap.c:233",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_folio",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:folio_add_lru",
        "mm/swap.c:folio_rotate_reclaimable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448032,
      "name": "folio_batch_move_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void folio_batch_move_lru(struct folio_batch * fbatch, move_fn_t move_fn)
```

```json
{
  "name": "folio_batch_move_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653120,
      "name": "folio_batch_move_lru",
      "external": false,
      "loc": "mm/swap.c:203",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:folio_mark_lazyfree",
        "mm/swap.c:folio_deactivate",
        "mm/swap.c:deactivate_file_folio",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:folio_add_lru",
        "mm/swap.c:folio_rotate_reclaimable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653120,
      "name": "folio_batch_move_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void folio_batch_move_lru(struct folio_batch * fbatch, move_fn_t move_fn)
```

```json
{
  "name": "folio_batch_move_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582824272,
      "name": "folio_batch_move_lru",
      "external": false,
      "loc": "mm/swap.c:203",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:folio_mark_lazyfree",
        "mm/swap.c:folio_deactivate",
        "mm/swap.c:deactivate_file_folio",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:folio_add_lru",
        "mm/swap.c:folio_rotate_reclaimable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824272,
      "name": "folio_batch_move_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void folio_batch_move_lru(struct folio_batch * fbatch, move_fn_t move_fn)
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
