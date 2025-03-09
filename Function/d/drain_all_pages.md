# Function: <code>drain_all_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494736,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1940",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494736,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584528,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2302",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memory-failure.c:shake_page",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584528,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651504,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2355",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memory-failure.c:shake_page",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651504,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580684048,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2463",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:SyS_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684048,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767520,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2498",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:SyS_madvise",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767520,
      "name": "drain_all_pages",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580903792,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2603",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/compaction.c:kcompactd_do_work",
        "mm/madvise.c:madvise_inject_error",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903792,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978432,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2700",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/compaction.c:kcompactd_do_work",
        "mm/madvise.c:madvise_inject_error",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978432,
      "name": "drain_all_pages",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401168,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2876",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:__do_sys_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401168,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462160,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:__do_sys_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462160,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581667424,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2959",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/madvise.c:madvise_inject_error",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667424,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581716993,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3127",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715504,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581737171,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3176",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735776,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582014024,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3252",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012064,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457689,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3274",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438544,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582971769,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3304",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947376,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583183607,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2338",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165632,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583367719,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2336",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349072,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492870336,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492870336,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226669392,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226669392,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286263104,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:__se_sys_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286263104,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272813728,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272813728,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431008,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:__do_sys_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431008,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373440,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:__do_sys_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373440,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422208,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:__do_sys_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422208,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void drain_all_pages(struct zone * zone)
```

```json
{
  "name": "drain_all_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486656,
      "name": "drain_all_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2867",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/madvise.c:__do_sys_madvise",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486656,
      "name": "drain_all_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
