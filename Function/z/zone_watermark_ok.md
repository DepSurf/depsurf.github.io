# Function: <code>zone_watermark_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580495312,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2421",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__compact_pgdat",
        "mm/compaction.c:try_to_compact_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495312,
      "name": "zone_watermark_ok",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580593168,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2781",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:__compact_pgdat",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580590800,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580655795,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657664,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580688110,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3015",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690496,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580771439,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3083",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776016,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580907629,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3187",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912032,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580982564,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3300",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987168,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404921,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3465",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405616,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581465916,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466608,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581672400,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3566",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_reporting.c:page_reporting_process_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673552,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581719880,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3690",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_reporting.c:page_reporting_process_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721536,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581740981,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3740",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742160,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582018686,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3911",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020032,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582445111,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3947",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446784,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582954378,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:4032",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/compaction.c:__compaction_suitable",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956112,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583171339,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:2964",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583173216,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583354943,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3035",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_unref_page_commit"
      ],
      "caller_func": [
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:should_abort_scan",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356960,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492874332,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492875296,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226674000,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226674112,
      "name": "zone_watermark_ok",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286267808,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286268880,
      "name": "zone_watermark_ok",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272817312,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272817398,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581434764,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435456,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581377148,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377840,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581425964,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426656,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool zone_watermark_ok(struct zone * z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags)
```

```json
{
  "name": "zone_watermark_ok",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581490444,
      "name": "zone_watermark_ok",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page"
      ],
      "caller_func": [
        "mm/compaction.c:__compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491104,
      "name": "zone_watermark_ok",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
