# Function: <code>free_unref_page</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768480,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:2672",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768480,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904688,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:2776",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904688,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979344,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:2875",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979344,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402128,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3051",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402128,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463120,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463120,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668416,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3134",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__put_page",
        "mm/page_alloc.c:free_contig_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:free_pages_exact",
        "mm/page_alloc.c:make_alloc_exact",
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668416,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716112,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3234",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:page_frag_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716112,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736240,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3283",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:page_frag_alloc_align"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736240,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void free_unref_page(struct page * page, unsigned int order)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012800,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3390",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:free_compound_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012800,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void free_unref_page(struct page * page, unsigned int order)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439488,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3428",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__put_page",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:free_compound_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439488,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void free_unref_page(struct page * page, unsigned int order)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948352,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3456",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__folio_put",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:__free_pages",
        "mm/page_alloc.c:__free_pages",
        "mm/page_alloc.c:free_compound_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948352,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
void free_unref_page(struct page * page, unsigned int order)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583165680,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:2435",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__folio_put",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:__free_pages",
        "mm/page_alloc.c:__free_pages",
        "mm/page_alloc.c:free_compound_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165680,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void free_unref_page(struct page * page, unsigned int order)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583349120,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:2478",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__folio_put",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:__free_pages",
        "mm/page_alloc.c:__free_pages",
        "mm/page_alloc.c:destroy_large_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349120,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492870944,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__put_page",
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492870944,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226670508,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226670508,
      "name": "free_unref_page",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286263968,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286263968,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272814294,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__put_page",
        "mm/page_alloc.c:free_contig_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272814294,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431968,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431968,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374400,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374400,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581423168,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581423168,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void free_unref_page(struct page * page)
```

```json
{
  "name": "free_unref_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487616,
      "name": "free_unref_page",
      "external": true,
      "loc": "mm/page_alloc.c:3042",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:page_frag_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487616,
      "name": "free_unref_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void free_unref_page(struct page * page)
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
