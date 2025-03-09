# Function: <code>__filemap_set_wb_err</code>

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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580640755,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:581",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/inode.c:__writepage",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641568,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580723571,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/inode.c:__writepage",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580724336,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580858819,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860112,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927301,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:652",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928432,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581023326,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:691",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025376,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078614,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080720,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265312,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:678",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_page_writeback",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265312,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306720,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:679",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_page_writeback",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306720,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323856,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:710",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323856,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569440,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:728",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/dir.c:fuse_flush_time_update",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569440,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581923776,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:697",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/dir.c:fuse_flush_time_update",
        "fs/fuse/file.c:fuse_vma_close",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923776,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361168,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:692",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/dir.c:fuse_flush_time_update",
        "fs/fuse/file.c:fuse_vma_close",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361168,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582564496,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:699",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:writepage_cb",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_write_end_io",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/dir.c:fuse_flush_time_update",
        "fs/fuse/file.c:fuse_vma_close",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564496,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735360,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:694",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:writepage_cb",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_write_end_io",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/dir.c:fuse_flush_time_update",
        "fs/fuse/file.c:fuse_vma_close",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735360,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492443896,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492443896,
      "name": "__filemap_set_wb_err",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226318476,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:shrink_page_list",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226319804,
      "name": "__filemap_set_wb_err",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285715760,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285718288,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272518200,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272519390,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581047462,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049568,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580994742,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580996848,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581038662,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040768,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
```

```json
{
  "name": "__filemap_set_wb_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581100278,
      "name": "__filemap_set_wb_err",
      "external": true,
      "loc": "mm/filemap.c:700",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__writepage",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/buffer.c:mark_buffer_write_io_error",
        "fs/mpage.c:__mpage_writepage",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102400,
      "name": "__filemap_set_wb_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void __filemap_set_wb_err(struct address_space * mapping, int err)
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
