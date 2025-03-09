# Function: <code>lru_add_drain_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541008,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:807",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_alloc_cpu_notify",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:__pagevec_release",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541008,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629216,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:584",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_alloc_cpu_notify",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629216,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580696432,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:585",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696432,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580730208,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:604",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580730208,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816208,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:604",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816208,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953200,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:577",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953200,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029360,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:571",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029360,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093392,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:572",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093392,
      "name": "lru_add_drain_cpu",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150112,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150112,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335680,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:626",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_cpu_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335680,
      "name": "lru_add_drain_cpu",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379216,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:611",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_cpu_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379216,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400176,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:614",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_cpu_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400176,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650800,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:592",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_cpu_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650800,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019552,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:596",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_cpu_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019552,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452480,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:676",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_cpu_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452480,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657760,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:646",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__folio_batch_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_cpu_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657760,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582828896,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:646",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__folio_batch_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:lru_add_drain_cpu_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582828896,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492526512,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_add_drain",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492526512,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226393816,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226393816,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285820688,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285820688,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272580238,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272580238,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118960,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118960,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065984,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065984,
      "name": "lru_add_drain_cpu",
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110160,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110160,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
void lru_add_drain_cpu(int cpu)
```

```json
{
  "name": "lru_add_drain_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172560,
      "name": "lru_add_drain_cpu",
      "external": true,
      "loc": "mm/swap.c:589",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_add_drain",
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:page_alloc_cpu_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172560,
      "name": "lru_add_drain_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
