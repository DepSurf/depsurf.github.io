# Function: <code>steal_suitable_fallback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580506998,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:1584",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580583885,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:1943",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__rmqueue"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580650447,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:1962",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__rmqueue"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580682788,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:1982",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__rmqueue"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone * zone, struct page * page, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766464,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2020",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766464,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void steal_suitable_fallback(struct zone * zone, struct page * page, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902736,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2129",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902736,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977200,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2199",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977200,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581396112,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2378",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396112,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457104,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457104,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662192,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2449",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662192,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710480,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2529",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710480,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731056,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2578",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731056,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2651",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005312,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    },
    {
      "addr": 18446744071592203544,
      "name": "steal_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2676",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431264,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
    },
    {
      "addr": 18446744071593981206,
      "name": "steal_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2755",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940000,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
    },
    {
      "addr": 18446744071596036817,
      "name": "steal_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:1801",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157312,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
    },
    {
      "addr": 18446744071596559026,
      "name": "steal_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:1764",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340352,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
    },
    {
      "addr": 18446744071597463373,
      "name": "steal_suitable_fallback.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492864504,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492864504,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226664068,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226664068,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286256224,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286256224,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272809494,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272809494,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425952,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425952,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581368432,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368432,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581417152,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417152,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void steal_suitable_fallback(struct zone * zone, struct page * page, unsigned int alloc_flags, int start_type, bool whole_block)
```

```json
{
  "name": "steal_suitable_fallback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581481408,
      "name": "steal_suitable_fallback",
      "external": false,
      "loc": "mm/page_alloc.c:2369",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481408,
      "name": "steal_suitable_fallback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void steal_suitable_fallback(struct zone * zone, struct page * page, int start_type, bool whole_block)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int alloc_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, page, start_type, whole_block</code> ➡️ <code>zone, page, alloc_flags, start_type, whole_block</code>
</li>
</ul>
</details>
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
