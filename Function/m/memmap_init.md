# Function: <code>memmap_init</code>

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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589482959,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:5802",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589482959,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942820,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:5988",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942820,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590170375,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590170375,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int range_start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591188528,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6089",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188528,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 205
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int range_start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591683938,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6303",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591683938,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 342
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
void memmap_init()
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614441940,
      "name": "memmap_init",
      "external": false,
      "loc": "mm/page_alloc.c:6531",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614441940,
      "name": "memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 415
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
void memmap_init()
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615383865,
      "name": "memmap_init",
      "external": false,
      "loc": "mm/page_alloc.c:6707",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615383865,
      "name": "memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 418
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
void memmap_init()
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617171136,
      "name": "memmap_init",
      "external": false,
      "loc": "mm/page_alloc.c:6828",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617171136,
      "name": "memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 456
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
void memmap_init()
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627861312,
      "name": "memmap_init",
      "external": false,
      "loc": "mm/page_alloc.c:7000",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627861312,
      "name": "memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 501
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
void memmap_init()
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619610672,
      "name": "memmap_init",
      "external": false,
      "loc": "mm/mm_init.c:923",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619610672,
      "name": "memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 501
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
void memmap_init()
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621914928,
      "name": "memmap_init",
      "external": false,
      "loc": "mm/mm_init.c:934",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621914928,
      "name": "memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 501
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503918208,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503918208,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3244023192,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3244023192,
      "name": "memmap_init",
      "section": ".init.text",
      "bind": "STB_WEAK",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297813056,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297813056,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270889512,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270889512,
      "name": "memmap_init",
      "section": ".init.text",
      "bind": "STB_WEAK",
      "size": 28
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589772663,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589772663,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495486,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495486,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590216071,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590216071,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
```

```json
{
  "name": "memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590266434,
      "name": "memmap_init",
      "external": true,
      "loc": "mm/page_alloc.c:6006",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590266434,
      "name": "memmap_init",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 17
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
void memmap_init(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn)
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
<code>long unsigned int range_start_pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start_pfn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>int nid</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int zone</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int range_start_pfn</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
