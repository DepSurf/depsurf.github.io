# Function: <code>zone_set_pageset_high_and_batch</code>

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
void zone_set_pageset_high_and_batch(struct zone * zone)
```

```json
{
  "name": "zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701680,
      "name": "zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:6456",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_update",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_zone_pageset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701680,
      "name": "zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void zone_set_pageset_high_and_batch(struct zone * zone)
```

```json
{
  "name": "zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723136,
      "name": "zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:6677",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_pcp_update",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_zone_pageset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723136,
      "name": "zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void zone_set_pageset_high_and_batch(struct zone * zone, int cpu_online)
```

```json
{
  "name": "zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:6920",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_zone_pageset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996656,
      "name": "zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071592202668,
      "name": "zone_set_pageset_high_and_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void zone_set_pageset_high_and_batch(struct zone * zone, int cpu_online)
```

```json
{
  "name": "zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:7041",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_zone_pageset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420864,
      "name": "zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071593979878,
      "name": "zone_set_pageset_high_and_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void zone_set_pageset_high_and_batch(struct zone * zone, int cpu_online)
```

```json
{
  "name": "zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:7214",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_zone_pageset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929200,
      "name": "zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071596035469,
      "name": "zone_set_pageset_high_and_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void zone_set_pageset_high_and_batch(struct zone * zone, int cpu_online)
```

```json
{
  "name": "zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:5420",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_zone_pageset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583144832,
      "name": "zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071596557572,
      "name": "zone_set_pageset_high_and_batch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void zone_set_pageset_high_and_batch(struct zone * zone, int cpu_online)
```

```json
{
  "name": "zone_set_pageset_high_and_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328720,
      "name": "zone_set_pageset_high_and_batch",
      "external": false,
      "loc": "mm/page_alloc.c:5513",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_zone_pageset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328720,
      "name": "zone_set_pageset_high_and_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void zone_set_pageset_high_and_batch(struct zone * zone)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu_online</code>
</li>
</ul>
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
