# Function: <code>wait_for_stable_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580519248,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2812",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:grab_cache_page_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519248,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580605184,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2872",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605184,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672096,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2839",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672096,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580705360,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2848",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705360,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790880,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2831",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790880,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927248,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2828",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927248,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003264,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2811",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003264,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066672,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2831",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066672,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581122640,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122640,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310272,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2852",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310272,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348368,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2844",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348368,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581367488,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2857",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581367488,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615920,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2912",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615920,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994064,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/folio-compat.c:36",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994064,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430448,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/folio-compat.c:36",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430448,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635680,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/folio-compat.c:37",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635680,
      "name": "wait_for_stable_page",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807040,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/folio-compat.c:37",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807040,
      "name": "wait_for_stable_page",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492494296,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492494296,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226365336,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226365336,
      "name": "wait_for_stable_page",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285781232,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285781232,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272554934,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272554934,
      "name": "wait_for_stable_page",
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091488,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091488,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038672,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038672,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082688,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082688,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void wait_for_stable_page(struct page * page)
```

```json
{
  "name": "wait_for_stable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145632,
      "name": "wait_for_stable_page",
      "external": true,
      "loc": "mm/page-writeback.c:2842",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:filemap_page_mkwrite",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145632,
      "name": "wait_for_stable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
