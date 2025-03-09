# Function: <code>move_freepages_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int move_freepages_block(struct zone * zone, struct page * page, int migratetype)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494416,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:1512",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494416,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580582752,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:1871",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580582752,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649264,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:1890",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649264,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681440,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:1908",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681440,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766144,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:1946",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766144,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902384,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2055",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902384,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976848,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2095",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976848,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395760,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2274",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395760,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456752,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456752,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661840,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2337",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661840,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710128,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2415",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710128,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730688,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2467",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730688,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2540",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592203473,
      "name": "move_freepages_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582004784,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2565",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593981135,
      "name": "move_freepages_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582430624,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2644",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596036746,
      "name": "move_freepages_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582939360,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:1690",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596558953,
      "name": "move_freepages_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071583156672,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:1653",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597463300,
      "name": "move_freepages_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071583339712,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492864064,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492864064,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226663672,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226663672,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286255712,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286255712,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272809184,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272809184,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425600,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425600,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581368080,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368080,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416800,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416800,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int move_freepages_block(struct zone * zone, struct page * page, int migratetype, int * num_movable)
```

```json
{
  "name": "move_freepages_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581481056,
      "name": "move_freepages_block",
      "external": true,
      "loc": "mm/page_alloc.c:2265",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481056,
      "name": "move_freepages_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * num_movable</code>
</li>
</ul>
</details>
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
