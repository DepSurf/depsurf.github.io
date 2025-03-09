# Function: <code>truncate_error_page</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581222720,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:557",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222720,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581353424,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:557",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353424,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:590",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501072,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071581510103,
      "name": "truncate_error_page.cold.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581587902,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:592",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587808,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071581595983,
      "name": "truncate_error_page.cold.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581697745,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:589",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697648,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581706975,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581771185,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:593",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771088,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581780411,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:591",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990800,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071582001782,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:617",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040784,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071591337494,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:621",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067248,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071591280194,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:776",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377056,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071592226326,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:773",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582878960,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071594005423,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583429664,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:837",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583429664,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583650768,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:934",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650768,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493227344,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:593",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493227344,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286746336,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:593",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286746336,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581739921,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:593",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739824,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581749147,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581678561,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:593",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678464,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581687771,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581731233,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:593",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731136,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581740459,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```

```json
{
  "name": "truncate_error_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581799521,
      "name": "truncate_error_page",
      "external": false,
      "loc": "mm/memory-failure.c:593",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799424,
      "name": "truncate_error_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581808715,
      "name": "truncate_error_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int truncate_error_page(struct page * p, long unsigned int pfn, struct address_space * mapping)
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
