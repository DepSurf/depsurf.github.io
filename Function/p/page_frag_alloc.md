# Function: <code>page_frag_alloc</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662064,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3961",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:napi_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662064,
      "name": "page_frag_alloc",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580695568,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4248",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:napi_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695568,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780976,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4367",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:napi_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780976,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916592,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4499",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:napi_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916592,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992016,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4670",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:napi_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992016,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410416,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4837",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410416,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471440,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471440,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677472,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4958",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677472,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725280,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:5132",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725280,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589134974,
      "name": "page_frag_alloc",
      "external": false,
      "loc": "include/linux/gfp.h:609",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
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
  "name": "page_frag_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589860364,
      "name": "page_frag_alloc",
      "external": false,
      "loc": "include/linux/gfp.h:630",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
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
  "name": "page_frag_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591383287,
      "name": "page_frag_alloc",
      "external": false,
      "loc": "include/linux/gfp.h:661",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
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
  "name": "page_frag_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593149662,
      "name": "page_frag_alloc",
      "external": false,
      "loc": "include/linux/gfp.h:311",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
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
  "name": "page_frag_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593603378,
      "name": "page_frag_alloc",
      "external": false,
      "loc": "include/linux/gfp.h:311",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
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
  "name": "page_frag_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594377970,
      "name": "page_frag_alloc",
      "external": false,
      "loc": "include/linux/gfp.h:319",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492879736,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492879736,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226679912,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226679912,
      "name": "page_frag_alloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286274448,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286274448,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272821684,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272821684,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440288,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440288,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581382672,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382672,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431488,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431488,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```

```json
{
  "name": "page_frag_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581495984,
      "name": "page_frag_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4855",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495984,
      "name": "page_frag_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void * page_frag_alloc(struct page_frag_cache * nc, unsigned int fragsz, gfp_t gfp_mask)
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
