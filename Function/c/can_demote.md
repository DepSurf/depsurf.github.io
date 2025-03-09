# Function: <code>can_demote</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_demote(int nid, struct scan_control * sc)
```

```json
{
  "name": "can_demote",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581680282,
      "name": "can_demote",
      "external": false,
      "loc": "mm/vmscan.c:525",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:zone_reclaimable_pages",
        "mm/vmscan.c:zone_reclaimable_pages"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_page_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664304,
      "name": "can_demote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071592191506,
      "name": "can_demote.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_demote(int nid, struct scan_control * sc)
```

```json
{
  "name": "can_demote",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582065843,
      "name": "can_demote",
      "external": false,
      "loc": "mm/vmscan.c:527",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:zone_reclaimable_pages"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_page_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039136,
      "name": "can_demote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071593967427,
      "name": "can_demote.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_demote(int nid, struct scan_control * sc)
```

```json
{
  "name": "can_demote",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582538514,
      "name": "can_demote",
      "external": false,
      "loc": "mm/vmscan.c:541",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:zone_reclaimable_pages"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_folio_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478976,
      "name": "can_demote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071596026031,
      "name": "can_demote.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_demote(int nid, struct scan_control * sc)
```

```json
{
  "name": "can_demote",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582748043,
      "name": "can_demote",
      "external": false,
      "loc": "mm/vmscan.c:593",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:zone_reclaimable_pages"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_folio_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582683872,
      "name": "can_demote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071596548208,
      "name": "can_demote.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool can_demote(int nid, struct scan_control * sc)
```

```json
{
  "name": "can_demote",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582915979,
      "name": "can_demote",
      "external": false,
      "loc": "mm/vmscan.c:299",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:zone_reclaimable_pages"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_folio_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854368,
      "name": "can_demote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071597451867,
      "name": "can_demote.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool can_demote(int nid, struct scan_control * sc)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
