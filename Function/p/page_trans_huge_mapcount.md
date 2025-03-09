# Function: <code>page_trans_huge_mapcount</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581034848,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:1925",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034848,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581110048,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2056",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110048,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581158400,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2380",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158400,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287968,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2532",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287968,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434992,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2524",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434992,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518528,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2543",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518528,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628352,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2604",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628352,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699168,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2627",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699168,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915152,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2537",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:page_trans_huge_map_swapcount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915152,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961872,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2594",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:page_trans_huge_map_swapcount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961872,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988048,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2605",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:page_trans_huge_map_swapcount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988048,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582290144,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2544",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:page_trans_huge_map_swapcount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290144,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493142816,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2627",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493142816,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226715908,
      "name": "page_trans_huge_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:734",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:reuse_swap_page"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286630256,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2627",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286630256,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272847634,
      "name": "page_trans_huge_mapcount",
      "external": false,
      "loc": "include/linux/mm.h:734",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:reuse_swap_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581667904,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2627",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667904,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581607440,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2627",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607440,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659216,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2627",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659216,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
```

```json
{
  "name": "page_trans_huge_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725600,
      "name": "page_trans_huge_mapcount",
      "external": true,
      "loc": "mm/huge_memory.c:2627",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725600,
      "name": "page_trans_huge_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
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
int page_trans_huge_mapcount(struct page * page, int * total_mapcount)
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
