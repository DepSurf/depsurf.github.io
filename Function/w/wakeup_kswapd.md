# Function: <code>wakeup_kswapd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone * zone, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559904,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3511",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559904,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void wakeup_kswapd(struct zone * zone, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651728,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3487",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651728,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void wakeup_kswapd(struct zone * zone, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718864,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3498",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718864,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void wakeup_kswapd(struct zone * zone, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754368,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3603",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754368,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void wakeup_kswapd(struct zone * zone, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841568,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3626",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841568,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978128,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3645",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978128,
      "name": "wakeup_kswapd",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055088,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3937",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055088,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119744,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3890",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119744,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176784,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176784,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378928,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3958",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378928,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422544,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3956",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422544,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581443824,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:4154",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581443824,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697872,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:4346",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697872,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073216,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:4493",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073216,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582548544,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:7433",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548544,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582754080,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:7797",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:numamigrate_isolate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582754080,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922304,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:7164",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue",
        "mm/migrate.c:migrate_misplaced_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922304,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492556944,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492556944,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226419436,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226419436,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285861376,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285861376,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272602046,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272602046,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145632,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145632,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092576,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092576,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136832,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136832,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void wakeup_kswapd(struct zone * zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx)
```

```json
{
  "name": "wakeup_kswapd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581199344,
      "name": "wakeup_kswapd",
      "external": true,
      "loc": "mm/vmscan.c:3976",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199344,
      "name": "wakeup_kswapd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, order, classzone_idx</code> ➡️ <code>zone, gfp_flags, order, classzone_idx</code>
</li>
</ul>
</details>
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
<code>enum zone_type highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>enum zone_type classzone_idx</code>
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
