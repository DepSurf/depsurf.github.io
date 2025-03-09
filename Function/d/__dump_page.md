# Function: <code>__dump_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763248,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:43",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:bad_page",
        "mm/debug.c:dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763248,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828864,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:43",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:bad_page",
        "mm/debug.c:dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828864,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870944,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:43",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:bad_page",
        "mm/debug.c:dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870944,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962192,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:44",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:bad_page",
        "mm/debug.c:dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962192,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:44",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:bad_page",
        "mm/debug.c:dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097152,
      "name": "__dump_page.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071581097008,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:bad_page",
        "mm/debug.c:dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176704,
      "name": "__dump_page.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071581176560,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246432,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071581246288,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304928,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071581304720,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496128,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
    },
    {
      "addr": 18446744071581495312,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 795
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591326818,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
    },
    {
      "addr": 18446744071581536960,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591269160,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
    },
    {
      "addr": 18446744071581558768,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void __dump_page(struct page * page)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": false,
      "loc": "mm/debug.c:47",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823040,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    },
    {
      "addr": 18446744071592197461,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
void __dump_page(struct page * page)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": false,
      "loc": "mm/debug.c:49",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214336,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071593974254,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
void __dump_page(struct page * page)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582702416,
      "name": "__dump_page",
      "external": false,
      "loc": "mm/debug.c:49",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702416,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
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
void __dump_page(struct page * page)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582916320,
      "name": "__dump_page",
      "external": false,
      "loc": "mm/debug.c:54",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916320,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
void __dump_page(struct page * page)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583090448,
      "name": "__dump_page",
      "external": false,
      "loc": "mm/debug.c:54",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090448,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492713808,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492713808,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226549420,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226549420,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286050992,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286050992,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272711536,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272711536,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273776,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071581273568,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220336,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071581220128,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264976,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071581264768,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void __dump_page(struct page * page, const char * reason)
```

```json
{
  "name": "__dump_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dump_page",
      "external": true,
      "loc": "mm/debug.c:45",
      "file": "mm/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:dump_page",
        "mm/page_alloc.c:bad_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328848,
      "name": "__dump_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071581328640,
      "name": "__dump_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void __dump_page(struct page * page, const char * reason)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const char * reason</code>
</li>
</ul>
</details>
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
