# Function: <code>errseq_set</code>

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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664624,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664624,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882304,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882304,
      "name": "errseq_set",
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583966480,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966480,
      "name": "errseq_set",
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146352,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146352,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584269008,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584269008,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584676928,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
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
      "addr": 18446744071584676928,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584794544,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:59",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
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
      "addr": 18446744071584794544,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584838688,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:59",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
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
      "addr": 18446744071584838688,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258064,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:59",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
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
      "addr": 18446744071585258064,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586100704,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:59",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:dio_warn_stale_pagecache",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
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
      "addr": 18446744071586100704,
      "name": "errseq_set",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587085552,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:59",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:dio_warn_stale_pagecache",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/page-writeback.c:__writepage",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:mark_buffer_write_io_error",
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
      "addr": 18446744071587085552,
      "name": "errseq_set",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587344560,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:59",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:dio_warn_stale_pagecache",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/page-writeback.c:writepage_cb",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:mark_buffer_write_io_error",
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
      "addr": 18446744071587344560,
      "name": "errseq_set",
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587628016,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:59",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:dio_warn_stale_pagecache",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/page-writeback.c:writepage_cb",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:me_pagecache_dirty",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:mark_buffer_write_io_error",
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
      "addr": 18446744071587628016,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496153048,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496153048,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229473580,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229473580,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290414176,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290414176,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275206170,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275206170,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237744,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237744,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172944,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172944,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584221504,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584221504,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
errseq_t errseq_set(errseq_t * eseq, int err)
```

```json
{
  "name": "errseq_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584326336,
      "name": "errseq_set",
      "external": true,
      "loc": "lib/errseq.c:58",
      "file": "lib/errseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584326336,
      "name": "errseq_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
errseq_t errseq_set(errseq_t * eseq, int err)
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
