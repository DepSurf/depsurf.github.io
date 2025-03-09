# Function: <code>lru_note_cost</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_pages)
```

```json
{
  "name": "lru_note_cost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581334480,
      "name": "lru_note_cost",
      "external": true,
      "loc": "mm/swap.c:281",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_note_cost_page",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334480,
      "name": "lru_note_cost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_pages)
```

```json
{
  "name": "lru_note_cost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376896,
      "name": "lru_note_cost",
      "external": true,
      "loc": "mm/swap.c:262",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_note_cost_page",
        "mm/swap.c:lru_note_cost_page",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376896,
      "name": "lru_note_cost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_pages)
```

```json
{
  "name": "lru_note_cost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397664,
      "name": "lru_note_cost",
      "external": true,
      "loc": "mm/swap.c:274",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_note_cost_page",
        "mm/swap.c:lru_note_cost_page",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397664,
      "name": "lru_note_cost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_pages)
```

```json
{
  "name": "lru_note_cost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647904,
      "name": "lru_note_cost",
      "external": true,
      "loc": "mm/swap.c:252",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_note_cost_page",
        "mm/swap.c:lru_note_cost_page",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647904,
      "name": "lru_note_cost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_pages)
```

```json
{
  "name": "lru_note_cost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582016864,
      "name": "lru_note_cost",
      "external": true,
      "loc": "mm/swap.c:264",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_note_cost_folio",
        "mm/swap.c:lru_note_cost_folio",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582016864,
      "name": "lru_note_cost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_io, unsigned int nr_rotated)
```

```json
{
  "name": "lru_note_cost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451216,
      "name": "lru_note_cost",
      "external": true,
      "loc": "mm/swap.c:299",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_note_cost_refault",
        "mm/swap.c:lru_note_cost_refault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451216,
      "name": "lru_note_cost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_io, unsigned int nr_rotated)
```

```json
{
  "name": "lru_note_cost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582656448,
      "name": "lru_note_cost",
      "external": true,
      "loc": "mm/swap.c:269",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_note_cost_refault",
        "mm/swap.c:lru_note_cost_refault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656448,
      "name": "lru_note_cost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_io, unsigned int nr_rotated)
```

```json
{
  "name": "lru_note_cost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582827584,
      "name": "lru_note_cost",
      "external": true,
      "loc": "mm/swap.c:269",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_note_cost_refault",
        "mm/swap.c:lru_note_cost_refault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827584,
      "name": "lru_note_cost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void lru_note_cost(struct lruvec * lruvec, bool file, unsigned int nr_pages)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_io</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_rotated</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_pages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
