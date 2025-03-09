# Function: <code>grab_cache_page_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475760,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:2470",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475760,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580554032,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:2648",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/iomap.c:iomap_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554032,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580618544,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:2764",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/iomap.c:iomap_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618544,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649680,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:2904",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649680,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580733712,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3080",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580733712,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869184,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3080",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869184,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943696,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3149",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943696,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035184,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3268",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035184,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090752,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090752,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284272,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3259",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284272,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328432,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3353",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328432,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338000,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3601",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338000,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586304,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3718",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586304,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993632,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/folio-compat.c:133",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993632,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430048,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/folio-compat.c:105",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430048,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635232,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/folio-compat.c:106",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635232,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806592,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/folio-compat.c:100",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806592,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492456520,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492456520,
      "name": "grab_cache_page_write_begin",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226330772,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226330772,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285740720,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285740720,
      "name": "grab_cache_page_write_begin",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272528252,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272528252,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059600,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059600,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006832,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006832,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050800,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050800,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct page * grab_cache_page_write_begin(struct address_space * mapping, long unsigned int index, unsigned int flags)
```

```json
{
  "name": "grab_cache_page_write_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112448,
      "name": "grab_cache_page_write_begin",
      "external": true,
      "loc": "mm/filemap.c:3225",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112448,
      "name": "grab_cache_page_write_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<b>Param removed. </b>
<code>unsigned int flags</code>
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
