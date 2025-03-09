# Function: <code>folio_lruvec_lock_irqsave</code>

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
struct lruvec * folio_lruvec_lock_irqsave(struct folio * folio, long unsigned int * flags)
```

```json
{
  "name": "folio_lruvec_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582848928,
      "name": "folio_lruvec_lock_irqsave",
      "external": true,
      "loc": "mm/memcontrol.c:1262",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848928,
      "name": "folio_lruvec_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct lruvec * folio_lruvec_lock_irqsave(struct folio * folio, long unsigned int * flags)
```

```json
{
  "name": "folio_lruvec_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583394864,
      "name": "folio_lruvec_lock_irqsave",
      "external": true,
      "loc": "mm/memcontrol.c:1342",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:__page_cache_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394864,
      "name": "folio_lruvec_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct lruvec * folio_lruvec_lock_irqsave(struct folio * folio, long unsigned int * flags)
```

```json
{
  "name": "folio_lruvec_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614096,
      "name": "folio_lruvec_lock_irqsave",
      "external": true,
      "loc": "mm/memcontrol.c:1366",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:__page_cache_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614096,
      "name": "folio_lruvec_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct lruvec * folio_lruvec_lock_irqsave(struct folio * folio, long unsigned int * flags)
```

```json
{
  "name": "folio_lruvec_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583808992,
      "name": "folio_lruvec_lock_irqsave",
      "external": true,
      "loc": "mm/memcontrol.c:1417",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:__page_cache_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808992,
      "name": "folio_lruvec_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct lruvec * folio_lruvec_lock_irqsave(struct folio * folio, long unsigned int * flags)
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
