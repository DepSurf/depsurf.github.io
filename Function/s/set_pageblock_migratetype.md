# Function: <code>set_pageblock_migratetype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505088,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:338",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505088,
      "name": "set_pageblock_migratetype",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581952,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:446",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581952,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580648464,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:451",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580648464,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680800,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:467",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680800,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765504,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:482",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765504,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901728,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:443",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901728,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976176,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:488",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976176,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581394976,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:550",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394976,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455968,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455968,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581671362,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:536",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581660736,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581718920,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:536",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581708928,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581739317,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:558",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_range",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729744,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582016596,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:561",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_range",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003552,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582443085,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:551",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": [
        "mm/page_alloc.c:__init_zone_device_page",
        "mm/page_alloc.c:memmap_init_range",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582427936,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596417757,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:608",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__init_zone_device_page",
        "mm/page_alloc.c:memmap_init_range",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936672,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583171973,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:449",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": [
        "mm/mm_init.c:memmap_init_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154112,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583355659,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:431",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback"
      ],
      "caller_func": [
        "mm/mm_init.c:memmap_init_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337264,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492863344,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492863344,
      "name": "set_pageblock_migratetype",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226663044,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226663044,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286254752,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286254752,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272808518,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272808518,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424816,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424816,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581367296,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581367296,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416016,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416016,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_pageblock_migratetype(struct page * page, int migratetype)
```

```json
{
  "name": "set_pageblock_migratetype",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480272,
      "name": "set_pageblock_migratetype",
      "external": true,
      "loc": "mm/page_alloc.c:537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480272,
      "name": "set_pageblock_migratetype",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
