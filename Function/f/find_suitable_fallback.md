# Function: <code>find_suitable_fallback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580491328,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:1610",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491328,
      "name": "find_suitable_fallback.part.72",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071580494688,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580583470,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:1969",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__rmqueue"
      ],
      "caller_func": [
        "mm/page_alloc.c:__rmqueue",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576000,
      "name": "find_suitable_fallback.part.78",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071580584384,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580650222,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:1988",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__rmqueue"
      ],
      "caller_func": [
        "mm/page_alloc.c:__rmqueue",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642368,
      "name": "find_suitable_fallback.part.79",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071580651360,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580682516,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2058",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:__rmqueue"
      ],
      "caller_func": [
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:__rmqueue",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674944,
      "name": "find_suitable_fallback.part.84",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071580683856,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580767248,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2096",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767248,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580903552,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2205",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903552,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580978160,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2284",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978160,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581397040,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2463",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397040,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581458032,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458032,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581663632,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2532",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_finished",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581663632,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581711872,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2611",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compact_finished",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711872,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581732176,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2660",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compact_finished",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732176,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582006566,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2733",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compact_finished",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592203575,
      "name": "find_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582006512,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2758",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compact_finished",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593981236,
      "name": "find_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582432720,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2837",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compact_finished",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596036847,
      "name": "find_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071582941488,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:1883",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compact_finished",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596559050,
      "name": "find_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583158800,
      "name": "find_suitable_fallback",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:1845",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compact_finished",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597463397,
      "name": "find_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583341744,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492865648,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492865648,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226665160,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226665160,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286257728,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286257728,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272810290,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272810290,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581426880,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426880,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581369360,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369360,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581418080,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418080,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int find_suitable_fallback(struct free_area * area, unsigned int order, int migratetype, bool only_stealable, bool * can_steal)
```

```json
{
  "name": "find_suitable_fallback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581482336,
      "name": "find_suitable_fallback",
      "external": true,
      "loc": "mm/page_alloc.c:2454",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482336,
      "name": "find_suitable_fallback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
