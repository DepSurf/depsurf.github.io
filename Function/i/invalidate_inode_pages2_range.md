# Function: <code>invalidate_inode_pages2_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580542864,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:563",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542864,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1111
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580631680,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:584",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631680,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1172
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698864,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:614",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698864,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1193
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732480,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:619",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_rw",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732480,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1207
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819152,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:672",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819152,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1365
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956224,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:668",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956224,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1369
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032208,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:669",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap.c:iomap_dio_rw",
        "fs/iomap.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032208,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1386
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:672",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101453,
      "name": "invalidate_inode_pages2_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581096224,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1326
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581153136,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153136,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1341
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339296,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339296,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1086
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581381280,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:712",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:truncate_bdev_range",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381280,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401984,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:609",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:truncate_bdev_range",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401984,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1281
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655040,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:608",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "block/bdev.c:truncate_bdev_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655040,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1342
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582020896,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:628",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "block/bdev.c:truncate_bdev_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020896,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1082
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455360,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:620",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "block/bdev.c:truncate_bdev_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455360,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1295
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660432,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:620",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:kiocb_invalidate_pages",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "block/bdev.c:truncate_bdev_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660432,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1289
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582831344,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:609",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:kiocb_invalidate_pages",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/inode.c:fuse_reverse_inval_inode",
        "block/bdev.c:truncate_bdev_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582831344,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1255
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492530760,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492530760,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1364
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226396656,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226396656,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285825584,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285825584,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1852
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272582824,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272582824,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121984,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121984,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1341
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068960,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068960,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1335
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113184,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113184,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1341
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
int invalidate_inode_pages2_range(struct address_space * mapping, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "invalidate_inode_pages2_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581175648,
      "name": "invalidate_inode_pages2_range",
      "external": true,
      "loc": "mm/truncate.c:684",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_direct_write",
        "mm/truncate.c:invalidate_inode_pages2",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_iomap_actor",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/fuse/inode.c:fuse_reverse_inval_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175648,
      "name": "invalidate_inode_pages2_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1322
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
