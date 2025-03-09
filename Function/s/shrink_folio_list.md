# Function: <code>shrink_folio_list</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int shrink_folio_list(struct list_head * folio_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_folio_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_folio_list",
      "external": false,
      "loc": "mm/vmscan.c:1651",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582515152,
      "name": "shrink_folio_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3072
    },
    {
      "addr": 18446744071596026351,
      "name": "shrink_folio_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int shrink_folio_list(struct list_head * folio_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_folio_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_folio_list",
      "external": false,
      "loc": "mm/vmscan.c:1705",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717104,
      "name": "shrink_folio_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3084
    },
    {
      "addr": 18446744071596548450,
      "name": "shrink_folio_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int shrink_folio_list(struct list_head * folio_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_folio_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_folio_list",
      "external": false,
      "loc": "mm/vmscan.c:1005",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582886448,
      "name": "shrink_folio_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3104
    },
    {
      "addr": 18446744071597452081,
      "name": "shrink_folio_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
unsigned int shrink_folio_list(struct list_head * folio_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
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
