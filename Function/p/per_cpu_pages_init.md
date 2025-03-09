# Function: <code>per_cpu_pages_init</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void per_cpu_pages_init(struct per_cpu_pages * pcp, struct per_cpu_zonestat * pzstats)
```

```json
{
  "name": "per_cpu_pages_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592202589,
      "name": "per_cpu_pages_init",
      "external": false,
      "loc": "mm/page_alloc.c:6883",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592202589,
      "name": "per_cpu_pages_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void per_cpu_pages_init(struct per_cpu_pages * pcp, struct per_cpu_zonestat * pzstats)
```

```json
{
  "name": "per_cpu_pages_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593979480,
      "name": "per_cpu_pages_init",
      "external": false,
      "loc": "mm/page_alloc.c:7004",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593979480,
      "name": "per_cpu_pages_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void per_cpu_pages_init(struct per_cpu_pages * pcp, struct per_cpu_zonestat * pzstats)
```

```json
{
  "name": "per_cpu_pages_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925344,
      "name": "per_cpu_pages_init",
      "external": false,
      "loc": "mm/page_alloc.c:7176",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925344,
      "name": "per_cpu_pages_init",
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
void per_cpu_pages_init(struct per_cpu_pages * pcp, struct per_cpu_zonestat * pzstats)
```

```json
{
  "name": "per_cpu_pages_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583143776,
      "name": "per_cpu_pages_init",
      "external": false,
      "loc": "mm/page_alloc.c:5382",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583143776,
      "name": "per_cpu_pages_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void per_cpu_pages_init(struct per_cpu_pages * pcp, struct per_cpu_zonestat * pzstats)
```

```json
{
  "name": "per_cpu_pages_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327392,
      "name": "per_cpu_pages_init",
      "external": false,
      "loc": "mm/page_alloc.c:5474",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_zone_pageset",
        "mm/page_alloc.c:build_all_zonelists_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327392,
      "name": "per_cpu_pages_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void per_cpu_pages_init(struct per_cpu_pages * pcp, struct per_cpu_zonestat * pzstats)
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
