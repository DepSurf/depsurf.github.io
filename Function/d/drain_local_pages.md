# Function: <code>drain_local_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502816,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:1919",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502816,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581760,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2281",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581760,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580648272,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2334",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580648272,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580680649,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2432",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_local_pages_wq"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684000,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580765097,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2467",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_local_pages_wq"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767472,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580899433,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2572",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_local_pages_wq"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903744,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978352,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2665",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/page_alloc.c:drain_local_pages_wq",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978352,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401088,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2841",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401088,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462080,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462080,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581660494,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2924",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_local_pages_wq"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/swap.c:lru_add_drain_cpu_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667312,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581708702,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3004",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_local_pages_wq"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/swap.c:lru_add_drain_cpu_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715392,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581729185,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3053",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_local_pages_wq"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/swap.c:lru_add_drain_cpu_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735664,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582002769,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3129",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_local_pages_wq"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/swap.c:lru_add_drain_cpu_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011952,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582423896,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3151",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:drain_local_pages_wq"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/swap.c:lru_add_drain_cpu_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438432,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947248,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:3211",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/swap.c:lru_add_drain_cpu_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947248,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583165504,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2245",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/swap.c:lru_add_drain_cpu_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165504,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348944,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2243",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/swap.c:lru_add_drain_cpu_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348944,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492870208,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492870208,
      "name": "drain_local_pages",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226669300,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226669300,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286262976,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286262976,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272813618,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272813618,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581430928,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430928,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373360,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373360,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422128,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422128,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void drain_local_pages(struct zone * zone)
```

```json
{
  "name": "drain_local_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486560,
      "name": "drain_local_pages",
      "external": true,
      "loc": "mm/page_alloc.c:2832",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:drain_local_pages_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486560,
      "name": "drain_local_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
