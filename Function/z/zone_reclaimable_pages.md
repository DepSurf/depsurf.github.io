# Function: <code>zone_reclaimable_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580550085,
      "name": "zone_reclaimable_pages",
      "external": false,
      "loc": "mm/vmscan.c:195",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pfmemalloc_watermark_ok",
        "mm/vmscan.c:zone_reclaimable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647136,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:202",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647136,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714304,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:202",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714304,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749616,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:209",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749616,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836896,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:210",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836896,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973520,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:255",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973520,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050192,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:324",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050192,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113792,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:336",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113792,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170752,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170752,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363296,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:301",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363296,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406896,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:294",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406896,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428144,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:526",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428144,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:572",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592191950,
      "name": "zone_reclaimable_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581680064,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:569",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:allow_direct_reclaim",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593967788,
      "name": "zone_reclaimable_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582056832,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:583",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:allow_direct_reclaim",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596026760,
      "name": "zone_reclaimable_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582529440,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:635",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:allow_direct_reclaim",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596548864,
      "name": "zone_reclaimable_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582732720,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:341",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:allow_direct_reclaim",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:compaction_zonelist_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597452517,
      "name": "zone_reclaimable_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582900640,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492550456,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492550456,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226414068,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226414068,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285852784,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285852784,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272596706,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272596706,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139600,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139600,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086544,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086544,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581130800,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130800,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
long unsigned int zone_reclaimable_pages(struct zone * zone)
```

```json
{
  "name": "zone_reclaimable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193264,
      "name": "zone_reclaimable_pages",
      "external": true,
      "loc": "mm/vmscan.c:333",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193264,
      "name": "zone_reclaimable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone * zone)
```
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
