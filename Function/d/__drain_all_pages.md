# Function: <code>__drain_all_pages</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __drain_all_pages(struct zone * zone, bool force_all_cpus)
```

```json
{
  "name": "__drain_all_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581703376,
      "name": "__drain_all_pages",
      "external": false,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703376,
      "name": "__drain_all_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
void __drain_all_pages(struct zone * zone, bool force_all_cpus)
```

```json
{
  "name": "__drain_all_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723968,
      "name": "__drain_all_pages",
      "external": false,
      "loc": "mm/page_alloc.c:3091",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723968,
      "name": "__drain_all_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
void __drain_all_pages(struct zone * zone, bool force_all_cpus)
```

```json
{
  "name": "__drain_all_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997168,
      "name": "__drain_all_pages",
      "external": false,
      "loc": "mm/page_alloc.c:3167",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997168,
      "name": "__drain_all_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
void __drain_all_pages(struct zone * zone, bool force_all_cpus)
```

```json
{
  "name": "__drain_all_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419168,
      "name": "__drain_all_pages",
      "external": false,
      "loc": "mm/page_alloc.c:3189",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419168,
      "name": "__drain_all_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
void __drain_all_pages(struct zone * zone, bool force_all_cpus)
```

```json
{
  "name": "__drain_all_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932192,
      "name": "__drain_all_pages",
      "external": false,
      "loc": "mm/page_alloc.c:3231",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932192,
      "name": "__drain_all_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void __drain_all_pages(struct zone * zone, bool force_all_cpus)
```

```json
{
  "name": "__drain_all_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583148560,
      "name": "__drain_all_pages",
      "external": false,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148560,
      "name": "__drain_all_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void __drain_all_pages(struct zone * zone, bool force_all_cpus)
```

```json
{
  "name": "__drain_all_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583333392,
      "name": "__drain_all_pages",
      "external": false,
      "loc": "mm/page_alloc.c:2263",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583333392,
      "name": "__drain_all_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __drain_all_pages(struct zone * zone, bool force_all_cpus)
```
</details>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
