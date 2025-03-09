# Function: <code>memmap_init_compound</code>

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
void memmap_init_compound(struct page * head, long unsigned int head_pfn, long unsigned int zone_idx, int nid, struct dev_pagemap * pgmap, long unsigned int nr_pages)
```

```json
{
  "name": "memmap_init_compound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594681582,
      "name": "memmap_init_compound",
      "external": false,
      "loc": "mm/page_alloc.c:6678",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594681582,
      "name": "memmap_init_compound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void memmap_init_compound(struct page * head, long unsigned int head_pfn, long unsigned int zone_idx, int nid, struct dev_pagemap * pgmap, long unsigned int nr_pages)
```

```json
{
  "name": "memmap_init_compound",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596417824,
      "name": "memmap_init_compound",
      "external": false,
      "loc": "mm/page_alloc.c:6853",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596417824,
      "name": "memmap_init_compound",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memmap_init_compound",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596957248,
      "name": "memmap_init_compound",
      "external": false,
      "loc": "mm/mm_init.c:1026",
      "file": "mm/mm_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:memmap_init_zone_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596957248,
      "name": "memmap_init_compound.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memmap_init_compound",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597884768,
      "name": "memmap_init_compound",
      "external": false,
      "loc": "mm/mm_init.c:1037",
      "file": "mm/mm_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:memmap_init_zone_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597884768,
      "name": "memmap_init_compound.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void memmap_init_compound(struct page * head, long unsigned int head_pfn, long unsigned int zone_idx, int nid, struct dev_pagemap * pgmap, long unsigned int nr_pages)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void memmap_init_compound(struct page * head, long unsigned int head_pfn, long unsigned int zone_idx, int nid, struct dev_pagemap * pgmap, long unsigned int nr_pages)
```
</details>
</li>
</ul>
