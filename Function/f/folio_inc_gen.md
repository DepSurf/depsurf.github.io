# Function: <code>folio_inc_gen</code>

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
int folio_inc_gen(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "folio_inc_gen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582490592,
      "name": "folio_inc_gen",
      "external": false,
      "loc": "mm/vmscan.c:3711",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490592,
      "name": "folio_inc_gen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
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
int folio_inc_gen(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "folio_inc_gen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582694240,
      "name": "folio_inc_gen",
      "external": false,
      "loc": "mm/vmscan.c:3796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694240,
      "name": "folio_inc_gen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1102
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
int folio_inc_gen(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
```

```json
{
  "name": "folio_inc_gen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582864080,
      "name": "folio_inc_gen",
      "external": false,
      "loc": "mm/vmscan.c:3117",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864080,
      "name": "folio_inc_gen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1099
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
int folio_inc_gen(struct lruvec * lruvec, struct folio * folio, bool reclaiming)
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
