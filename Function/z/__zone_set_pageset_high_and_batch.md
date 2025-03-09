# Function: <code>__zone_set_pageset_high_and_batch</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581728312,
      "name": "__zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:6440",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_pcp_enable",
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581750721,
      "name": "__zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:6661",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_pcp_enable",
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582030813,
      "name": "__zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:6904",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_pcp_enable",
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582459034,
      "name": "__zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:7025",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_pcp_enable",
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __zone_set_pageset_high_and_batch(struct zone * zone, long unsigned int high, long unsigned int batch)
```

```json
{
  "name": "__zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582929008,
      "name": "__zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:7198",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_enable",
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929008,
      "name": "__zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void __zone_set_pageset_high_and_batch(struct zone * zone, long unsigned int high, long unsigned int batch)
```

```json
{
  "name": "__zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583144640,
      "name": "__zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:5404",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_enable",
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583144640,
      "name": "__zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void __zone_set_pageset_high_and_batch(struct zone * zone, long unsigned int high_min, long unsigned int high_max, long unsigned int batch)
```

```json
{
  "name": "__zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328288,
      "name": "__zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:5497",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_enable",
        "mm/page_alloc.c:zone_pcp_disable",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328288,
      "name": "__zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void __zone_set_pageset_high_and_batch(struct zone * zone, long unsigned int high, long unsigned int batch)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int high_min</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int high_max</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int high</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, high, batch</code> ➡️ <code>zone, high_min, high_max, batch</code>
</li>
</ul>
</details>
</li>
</ul>
