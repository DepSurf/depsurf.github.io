# Function: <code>add_to_page_cache_lru</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475168,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:679",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_fault",
        "mm/readahead.c:read_cache_pages",
        "mm/readahead.c:__do_page_cache_readahead",
        "fs/splice.c:__generic_file_splice_read",
        "fs/mpage.c:mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475168,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553136,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:715",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:read_cache_pages",
        "fs/splice.c:__generic_file_splice_read",
        "fs/mpage.c:mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553136,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580617648,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:679",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617648,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647648,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:797",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647648,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731344,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:898",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731344,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865968,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:898",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865968,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580937088,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:879",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937088,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032064,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:927",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032064,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087616,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087616,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273680,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:911",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:page_cache_readahead_unbounded",
        "mm/readahead.c:read_cache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273680,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315472,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_cache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315472,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330976,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:960",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_cache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330976,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581581872,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:977",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_cache_pages",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581872,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int index, gfp_t gfp)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994944,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/folio-compat.c:113",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994944,
      "name": "add_to_page_cache_lru",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int index, gfp_t gfp)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431232,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/folio-compat.c:85",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/secretmem.c:secretmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431232,
      "name": "add_to_page_cache_lru",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int index, gfp_t gfp)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582636576,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/folio-compat.c:86",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/secretmem.c:secretmem_fault",
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "fs/squashfs/block.c:squashfs_bio_read_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636576,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int index, gfp_t gfp)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807952,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/folio-compat.c:80",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "fs/squashfs/block.c:squashfs_bio_read_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807952,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492454208,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492454208,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226327596,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226327596,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285729072,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285729072,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272525720,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272525720,
      "name": "add_to_page_cache_lru",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056464,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056464,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003712,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003712,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581047664,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047664,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int add_to_page_cache_lru(struct page * page, struct address_space * mapping, long unsigned int offset, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_page_cache_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109360,
      "name": "add_to_page_cache_lru",
      "external": true,
      "loc": "mm/filemap.c:936",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages",
        "fs/mpage.c:mpage_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109360,
      "name": "add_to_page_cache_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
