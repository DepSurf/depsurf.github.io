# Function: <code>free_pcp_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580585215,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1047",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_hot_cold_page"
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
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580652188,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1063",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_hot_cold_page"
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
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580685084,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1077",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_hot_cold_page"
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761232,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1091",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761232,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580896880,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1049",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580896880,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971600,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1094",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971600,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389504,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1215",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389504,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449728,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449728,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655696,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1252",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655696,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581703808,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1314",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703808,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725456,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1349",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725456,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
bool free_pcp_prepare(struct page * page, unsigned int order)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1408",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998176,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071592202698,
      "name": "free_pcp_prepare.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
bool free_pcp_prepare(struct page * page, unsigned int order)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1434",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426608,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071593980292,
      "name": "free_pcp_prepare.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
bool free_pcp_prepare(struct page * page, unsigned int order)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1514",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935248,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
    },
    {
      "addr": 18446744071596036103,
      "name": "free_pcp_prepare.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492858592,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492858592,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226657088,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226657088,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286246976,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286246976,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272803468,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272803468,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418576,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418576,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361088,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361088,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409776,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409776,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
bool free_pcp_prepare(struct page * page)
```

```json
{
  "name": "free_pcp_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473872,
      "name": "free_pcp_prepare",
      "external": false,
      "loc": "mm/page_alloc.c:1202",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473872,
      "name": "free_pcp_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
bool free_pcp_prepare(struct page * page)
```
</details>
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
<b>Param added. </b>
<code>unsigned int order</code>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool free_pcp_prepare(struct page * page, unsigned int order)
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
