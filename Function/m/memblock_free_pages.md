# Function: <code>memblock_free_pages</code>

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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604767833,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1380",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604767833,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604886987,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1490",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604886987,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604920895,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604920895,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609235257,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1536",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609235257,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612301614,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1619",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612301614,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614441770,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1654",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614441770,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615383514,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1740",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615383514,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617170762,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617170762,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627860816,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1804",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627860816,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619620336,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/mm_init.c:2577",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:free_low_memory_core_early",
        "mm/memblock.c:memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619620336,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621924480,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/mm_init.c:2565",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621924480,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510959316,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510959316,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243448376,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243448376,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302611172,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302611172,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270686916,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270686916,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604826355,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604826355,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604795416,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604795416,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604903539,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604903539,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
```

```json
{
  "name": "memblock_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604925076,
      "name": "memblock_free_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604925076,
      "name": "memblock_free_pages",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void memblock_free_pages(struct page * page, long unsigned int pfn, unsigned int order)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
