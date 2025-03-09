# Function: <code>__isolate_free_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505168,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2118",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:split_free_page",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505168,
      "name": "__isolate_free_page",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587136,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2480",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587136,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580654080,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2533",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654080,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686912,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2686",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686912,
      "name": "__isolate_free_page",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770160,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2744",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770160,
      "name": "__isolate_free_page",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906400,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2848",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906400,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981184,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2947",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981184,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403856,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3123",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403856,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464848,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464848,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671008,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3206",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_reporting.c:page_reporting_cycle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671008,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718576,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3307",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_reporting.c:page_reporting_cycle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718576,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738976,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3356",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_reporting.c:page_reporting_cycle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738976,
      "name": "__isolate_free_page",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3503",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_reporting.c:page_reporting_cycle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592204317,
      "name": "__isolate_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071582016176,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3536",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_reporting.c:page_reporting_cycle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593981751,
      "name": "__isolate_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071582442368,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 853
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3602",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_reporting.c:page_reporting_cycle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596037345,
      "name": "__isolate_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071582951536,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2581",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_reporting.c:page_reporting_cycle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596559564,
      "name": "__isolate_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071583168432,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:2624",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_reporting.c:page_reporting_cycle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597463968,
      "name": "__isolate_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071583352000,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492873312,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492873312,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226673536,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226673536,
      "name": "__isolate_free_page",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286266464,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286266464,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272817012,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272817012,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433696,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433696,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376080,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376080,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424896,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424896,
      "name": "__isolate_free_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int __isolate_free_page(struct page * page, unsigned int order)
```

```json
{
  "name": "__isolate_free_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489376,
      "name": "__isolate_free_page",
      "external": true,
      "loc": "mm/page_alloc.c:3114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_freepages_block",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489376,
      "name": "__isolate_free_page",
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
