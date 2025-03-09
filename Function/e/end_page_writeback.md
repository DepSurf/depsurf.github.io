# Function: <code>end_page_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580472976,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:823",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:end_swap_bio_write",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/migrate.c:migrate_page_copy",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472976,
      "name": "end_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580549776,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:864",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_copy",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549776,
      "name": "end_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580611600,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:967",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_copy",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611600,
      "name": "end_page_writeback",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580640016,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1093",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_copy",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640016,
      "name": "end_page_writeback",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580722720,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1215",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722720,
      "name": "end_page_writeback",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858064,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1215",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858064,
      "name": "end_page_writeback",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926480,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1268",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926480,
      "name": "end_page_writeback",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581023104,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1316",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023104,
      "name": "end_page_writeback",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078352,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078352,
      "name": "end_page_writeback",
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265200,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1300",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_page_writeback",
        "fs/iomap/buffered-io.c:iomap_finish_page_writeback",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265200,
      "name": "end_page_writeback",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310144,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1477",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_page_writeback",
        "fs/iomap/buffered-io.c:iomap_finish_page_writeback",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310144,
      "name": "end_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581327104,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1527",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327104,
      "name": "end_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574688,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1582",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "block/bdev.c:bdev_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574688,
      "name": "end_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993872,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:24",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "block/bdev.c:bdev_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993872,
      "name": "end_page_writeback",
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430224,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:24",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "block/bdev.c:bdev_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430224,
      "name": "end_page_writeback",
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635424,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:25",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:__end_swap_bio_write",
        "mm/page_io.c:__end_swap_bio_write",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635424,
      "name": "end_page_writeback",
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806784,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:25",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_write_complete",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806784,
      "name": "end_page_writeback",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492446352,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492446352,
      "name": "end_page_writeback",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226318188,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226318188,
      "name": "end_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285715312,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285715312,
      "name": "end_page_writeback",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272517944,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272517944,
      "name": "end_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581047200,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047200,
      "name": "end_page_writeback",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580994480,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994480,
      "name": "end_page_writeback",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581038400,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038400,
      "name": "end_page_writeback",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void end_page_writeback(struct page * page)
```

```json
{
  "name": "end_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581100016,
      "name": "end_page_writeback",
      "external": true,
      "loc": "mm/filemap.c:1325",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/migrate.c:migrate_page_states",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:end_buffer_async_write",
        "fs/block_dev.c:bdev_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100016,
      "name": "end_page_writeback",
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
