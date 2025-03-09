# Function: <code>prep_new_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580507974,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1364",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580588316,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1732",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580655221,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1751",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580689379,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1764",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
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
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580773774,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1802",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
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
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580909782,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1909",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
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
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580985484,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1953",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389776,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2150",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389776,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450000,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450000,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581660992,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2213",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581660992,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581720565,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2294",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581747123,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2345",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582025259,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2423",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582452166,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2449",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582961224,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2528",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583178130,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1574",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583361988,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:1537",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492856464,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492856464,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226657456,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226657456,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286247616,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286247616,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272803776,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272803776,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418848,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418848,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361360,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361360,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410048,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410048,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
```

```json
{
  "name": "prep_new_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475120,
      "name": "prep_new_page",
      "external": false,
      "loc": "mm/page_alloc.c:2141",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475120,
      "name": "prep_new_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void prep_new_page(struct page * page, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags)
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
