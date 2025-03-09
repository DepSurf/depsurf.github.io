# Function: <code>rmqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580687437,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:2813",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580770715,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:2870",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580907106,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:2974",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580981976,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3075",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397184,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3250",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397184,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3825
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458176,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458176,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3825
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581665344,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3352",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665344,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1890
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713536,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3454",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713536,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1792
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581733488,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3504",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733488,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2094
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3675",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008864,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2975
    },
    {
      "addr": 18446744071592203770,
      "name": "rmqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3711",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435680,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2649
    },
    {
      "addr": 18446744071593981565,
      "name": "rmqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3818",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944000,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3114
    },
    {
      "addr": 18446744071596037049,
      "name": "rmqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:2807",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161616,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3746
    },
    {
      "addr": 18446744071596559385,
      "name": "rmqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:2885",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344832,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3807
    },
    {
      "addr": 18446744071597463789,
      "name": "rmqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492865856,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492865856,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4232
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226666832,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226666832,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2468
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286257984,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286257984,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4856
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272811716,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272811716,
      "name": "rmqueue.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1902
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427024,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427024,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3825
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369504,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369504,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3793
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418224,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418224,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3825
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
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```

```json
{
  "name": "rmqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483968,
      "name": "rmqueue",
      "external": false,
      "loc": "mm/page_alloc.c:3241",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483968,
      "name": "rmqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2526
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct page * rmqueue(struct zone * preferred_zone, struct zone * zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype)
```
</details>
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
