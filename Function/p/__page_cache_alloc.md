# Function: <code>__page_cache_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580472784,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:708",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_fault",
        "mm/readahead.c:__do_page_cache_readahead",
        "fs/splice.c:__generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472784,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580549552,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:748",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead",
        "fs/splice.c:__generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549552,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580612080,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:712",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612080,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580640496,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:830",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640496,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580723296,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:931",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580723296,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580858544,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:931",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858544,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927024,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:909",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927024,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581022960,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:957",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022960,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078208,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:966",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078208,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581281501,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:941",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:page_cache_readahead_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262608,
      "name": "__page_cache_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071581262720,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581325482,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:966",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304608,
      "name": "__page_cache_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071581304736,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322656,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:990",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322656,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568288,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:1007",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568288,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581997409,
      "name": "__page_cache_alloc",
      "external": false,
      "loc": "include/linux/pagemap.h:480",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand"
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
  "name": "__page_cache_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582433333,
      "name": "__page_cache_alloc",
      "external": false,
      "loc": "include/linux/pagemap.h:478",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492441472,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:966",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492441472,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
  "name": "__page_cache_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226329668,
      "name": "__page_cache_alloc",
      "external": false,
      "loc": "include/linux/pagemap.h:213",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226382328,
      "name": "__page_cache_alloc",
      "external": false,
      "loc": "include/linux/pagemap.h:213",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285715024,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:966",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285715024,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
  "name": "__page_cache_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272527228,
      "name": "__page_cache_alloc",
      "external": false,
      "loc": "include/linux/pagemap.h:213",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272570084,
      "name": "__page_cache_alloc",
      "external": false,
      "loc": "include/linux/pagemap.h:213",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581047056,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:966",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047056,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580994336,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:966",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994336,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581038256,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:966",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038256,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
```

```json
{
  "name": "__page_cache_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581099872,
      "name": "__page_cache_alloc",
      "external": true,
      "loc": "mm/filemap.c:966",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099872,
      "name": "__page_cache_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct page * __page_cache_alloc(gfp_t gfp)
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
struct page * __page_cache_alloc(gfp_t gfp)
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
struct page * __page_cache_alloc(gfp_t gfp)
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
