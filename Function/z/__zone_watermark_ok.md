# Function: <code>__zone_watermark_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580489664,
      "name": "__zone_watermark_ok",
      "external": false,
      "loc": "mm/page_alloc.c:2353",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489664,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580586800,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2713",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586800,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580653744,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2764",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653744,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686608,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2947",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686608,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769824,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3004",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769824,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906064,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3108",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906064,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980848,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3221",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980848,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403520,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3386",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403520,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464512,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464512,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581671148,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3488",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671536,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581718711,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3626",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719088,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581746737,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3676",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739488,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582024999,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3847",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592204475,
      "name": "__zone_watermark_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582016928,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582451898,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3883",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593981917,
      "name": "__zone_watermark_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582443408,
      "name": "__zone_watermark_ok",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582960954,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3968",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596037511,
      "name": "__zone_watermark_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582952592,
      "name": "__zone_watermark_ok",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583177868,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2886",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596559751,
      "name": "__zone_watermark_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583169520,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583361724,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2957",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_unref_page_commit"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597464150,
      "name": "__zone_watermark_ok.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583352848,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492872912,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492872912,
      "name": "__zone_watermark_ok",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226672036,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226672036,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286266080,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286266080,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272815762,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272815762,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433360,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433360,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375744,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375744,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424560,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424560,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool __zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages)
```

```json
{
  "name": "__zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489040,
      "name": "__zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3377",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:zone_watermark_ok_safe",
        "mm/page_alloc.c:__isolate_free_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489040,
      "name": "__zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int alloc_flags</code> ➡️ <code>unsigned int alloc_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
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
