# Function: <code>iomap_apply</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580912,
      "name": "iomap_apply",
      "external": false,
      "loc": "fs/iomap.c:45",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_fiemap",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/iomap.c:iomap_zero_range",
        "fs/iomap.c:iomap_file_buffered_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580912,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669744,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap.c:43",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_fiemap",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/iomap.c:iomap_zero_range",
        "fs/iomap.c:iomap_file_dirty",
        "fs/iomap.c:iomap_file_buffered_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669744,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723824,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap.c:45",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_seek_data",
        "fs/iomap.c:iomap_seek_hole",
        "fs/iomap.c:iomap_fiemap",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/iomap.c:iomap_zero_range",
        "fs/iomap.c:iomap_file_dirty",
        "fs/iomap.c:iomap_file_buffered_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723824,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581869856,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap.c:45",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_seek_data",
        "fs/iomap.c:iomap_seek_hole",
        "fs/iomap.c:iomap_fiemap",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/iomap.c:iomap_zero_range",
        "fs/iomap.c:iomap_file_dirty",
        "fs/iomap.c:iomap_file_buffered_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869856,
      "name": "iomap_apply",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052512,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap.c:47",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap.c:iomap_bmap",
        "fs/iomap.c:iomap_swapfile_activate",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_seek_data",
        "fs/iomap.c:iomap_seek_hole",
        "fs/iomap.c:iomap_fiemap",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/iomap.c:iomap_zero_range",
        "fs/iomap.c:iomap_file_dirty",
        "fs/iomap.c:iomap_file_buffered_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052512,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145856,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap.c:48",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap.c:iomap_bmap",
        "fs/iomap.c:iomap_swapfile_activate",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_seek_data",
        "fs/iomap.c:iomap_seek_hole",
        "fs/iomap.c:iomap_fiemap",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/iomap.c:iomap_zero_range",
        "fs/iomap.c:iomap_file_dirty",
        "fs/iomap.c:iomap_file_buffered_write",
        "fs/iomap.c:iomap_readpages",
        "fs/iomap.c:iomap_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145856,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297712,
      "name": "iomap_apply.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071582297392,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582396400,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582396400,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685376,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:24",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685376,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582756704,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:24",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582756704,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582785696,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:24",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582785696,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493997040,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493997040,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227460812,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227460812,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287643488,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287643488,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273512158,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273512158,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582365136,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365136,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302832,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302832,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582355616,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582355616,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
```

```json
{
  "name": "iomap_apply",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435232,
      "name": "iomap_apply",
      "external": true,
      "loc": "fs/iomap/apply.c:23",
      "file": "fs/iomap/apply.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_dirty",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435232,
      "name": "iomap_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, struct iomap_ops * ops, void * data, iomap_actor_t actor)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops * ops</code> ➡️ <code>const struct iomap_ops * ops</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
loff_t iomap_apply(struct inode * inode, loff_t pos, loff_t length, unsigned int flags, const struct iomap_ops * ops, void * data, iomap_actor_t actor)
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
