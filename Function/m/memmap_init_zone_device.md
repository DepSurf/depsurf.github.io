# Function: <code>memmap_init_zone_device</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589465504,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:5719",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589465504,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589925616,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:5906",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589925616,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590151728,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:5924",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590151728,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591170096,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:6007",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591170096,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591665856,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:6175",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591665856,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591609984,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:6377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591609984,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592783248,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:6561",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592783248,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594682048,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:6707",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594682048,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596418384,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:6880",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596418384,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596958096,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/mm_init.c:1053",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596958096,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
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
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597885616,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/mm_init.c:1064",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597885616,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286286352,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:5924",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286286352,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589754016,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:5924",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589754016,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589478240,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:5924",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589478240,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590197424,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:5924",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197424,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```

```json
{
  "name": "memmap_init_zone_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590247856,
      "name": "memmap_init_zone_device",
      "external": true,
      "loc": "mm/page_alloc.c:5924",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590247856,
      "name": "memmap_init_zone_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int size</code>
</li>
</ul>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void memmap_init_zone_device(struct zone * zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap * pgmap)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
