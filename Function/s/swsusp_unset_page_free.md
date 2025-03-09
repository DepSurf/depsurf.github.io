# Function: <code>swsusp_unset_page_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699575,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:901",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_write_next"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701376,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579725750,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:999",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721152,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753274,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:999",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748656,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749537,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1001",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579744848,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579782860,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1003",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778160,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579814721,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1003",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811584,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579861473,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1004",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858336,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579895651,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1005",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892480,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579945923,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1012",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942752,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579984496,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1011",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:free_unnecessary_pages",
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987616,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579969264,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1045",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:free_unnecessary_pages",
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972384,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579971905,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1045",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:create_zone_bm_rtree",
        "kernel/power/snapshot.c:create_zone_bm_rtree"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974688,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103393,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1038",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106208,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580242295,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1042",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245136,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580447492,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1042",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443104,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580517462,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1042",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513120,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580578502,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1052",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573360,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225149508,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1012",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:restore_highmem",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225149508,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579913699,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1011",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910528,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579852931,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1012",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849760,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579906195,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1012",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903024,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void swsusp_unset_page_free(struct page * page)
```

```json
{
  "name": "swsusp_unset_page_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579952259,
      "name": "swsusp_unset_page_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1012",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ],
      "caller_func": [
        "mm/page_alloc.c:mark_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949056,
      "name": "swsusp_unset_page_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void swsusp_unset_page_free(struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void swsusp_unset_page_free(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void swsusp_unset_page_free(struct page * page)
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
