# Function: <code>has_unmovable_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, bool skip_hwpoisoned_pages)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580504656,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:6504",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:is_pageblock_removable_nolock"
      ],
      "caller_func": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504656,
      "name": "has_unmovable_pages.part.83",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071580513728,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, bool skip_hwpoisoned_pages)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580599660,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:7035",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:is_pageblock_removable_nolock"
      ],
      "caller_func": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580579952,
      "name": "has_unmovable_pages.part.88",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071580599504,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, bool skip_hwpoisoned_pages)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580666697,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:7087",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:is_pageblock_removable_nolock"
      ],
      "caller_func": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646496,
      "name": "has_unmovable_pages.part.89",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071580666544,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, bool skip_hwpoisoned_pages)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580699929,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:7414",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:is_pageblock_removable_nolock"
      ],
      "caller_func": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678816,
      "name": "has_unmovable_pages.part.94",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071580699792,
      "name": "has_unmovable_pages",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, bool skip_hwpoisoned_pages)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580784944,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:7429",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784944,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, bool skip_hwpoisoned_pages)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918384,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:7611",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918384,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993872,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:7932",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993872,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412608,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8139",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412608,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473632,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473632,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
struct page * has_unmovable_pages(struct zone * zone, struct page * page, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679440,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8196",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679440,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
struct page * has_unmovable_pages(struct zone * zone, struct page * page, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581727184,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8333",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581727184,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
struct page * has_unmovable_pages(struct zone * zone, struct page * page, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749552,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8542",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749552,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
struct page * has_unmovable_pages(struct zone * zone, struct page * page, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8807",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592207546,
      "name": "has_unmovable_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071582029424,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "has_unmovable_pages",
      "external": false,
      "loc": "mm/page_isolation.c:33",
      "file": "mm/page_isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582899280,
      "name": "has_unmovable_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
    },
    {
      "addr": 18446744071594006960,
      "name": "has_unmovable_pages.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "has_unmovable_pages",
      "external": false,
      "loc": "mm/page_isolation.c:33",
      "file": "mm/page_isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451360,
      "name": "has_unmovable_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    },
    {
      "addr": 18446744071596049388,
      "name": "has_unmovable_pages.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "has_unmovable_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "has_unmovable_pages",
      "external": false,
      "loc": "mm/page_isolation.c:33",
      "file": "mm/page_isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671264,
      "name": "has_unmovable_pages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    },
    {
      "addr": 18446744071596571887,
      "name": "has_unmovable_pages.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "has_unmovable_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "has_unmovable_pages",
      "external": false,
      "loc": "mm/page_isolation.c:33",
      "file": "mm/page_isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865696,
      "name": "has_unmovable_pages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
    },
    {
      "addr": 18446744071597476407,
      "name": "has_unmovable_pages.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492884624,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492884624,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226683576,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226683576,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286281040,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286281040,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272825160,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272825160,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442480,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442480,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384864,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384864,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433680,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433680,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
bool has_unmovable_pages(struct zone * zone, struct page * page, int count, int migratetype, int flags)
```

```json
{
  "name": "has_unmovable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498176,
      "name": "has_unmovable_pages",
      "external": true,
      "loc": "mm/page_alloc.c:8169",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498176,
      "name": "has_unmovable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int migratetype</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, page, count, skip_hwpoisoned_pages</code> ➡️ <code>zone, page, count, migratetype, skip_hwpoisoned_pages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool skip_hwpoisoned_pages</code>
</li>
</ul>
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
<b>Param removed. </b>
<code>int count</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, page, count, migratetype, flags</code> ➡️ <code>zone, page, migratetype, flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>struct page *</code>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct page * has_unmovable_pages(struct zone * zone, struct page * page, int migratetype, int flags)
```
</details>
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
