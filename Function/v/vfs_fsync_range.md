# Function: <code>vfs_fsync_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205904,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:183",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:SyS_msync",
        "fs/sync.c:do_fsync",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/direct-io.c:dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205904,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370576,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:183",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:SyS_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370576,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448432,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:184",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:SyS_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/iomap.c:iomap_dio_complete_work",
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448432,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502592,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:184",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:SyS_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/iomap.c:iomap_dio_complete_work",
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502592,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581644736,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:185",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:SyS_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap.c:iomap_dio_complete_work",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644736,
      "name": "vfs_fsync_range",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803568,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803568,
      "name": "vfs_fsync_range",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890576,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890576,
      "name": "vfs_fsync_range",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015680,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015680,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093632,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093632,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582330835,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:193",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__do_sys_msync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:io_issue_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330288,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582382259,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:193",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__do_sys_msync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:io_issue_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381712,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410018,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:192",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__do_sys_msync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/block_dev.c:blkdev_write_iter",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:io_issue_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408992,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582731410,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:193",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__do_sys_msync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:io_issue_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "block/fops.c:blkdev_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730864,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583277654,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:180",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__do_sys_msync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "block/fops.c:blkdev_write_iter",
        "io_uring/io_uring.c:io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276480,
      "name": "vfs_fsync_range",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583860310,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:180",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__do_sys_msync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "block/fops.c:blkdev_write_iter",
        "io_uring/sync.c:io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859008,
      "name": "vfs_fsync_range",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584082054,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:180",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__do_sys_msync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "block/fops.c:blkdev_write_iter",
        "io_uring/sync.c:io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584080752,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584298118,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:180",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync"
      ],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__do_sys_msync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "block/fops.c:blkdev_write_iter",
        "io_uring/sync.c:io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296816,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493629720,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__arm64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493629720,
      "name": "vfs_fsync_range",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227169940,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__se_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227169940,
      "name": "vfs_fsync_range",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287219952,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__se_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287219952,
      "name": "vfs_fsync_range",
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273269810,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__se_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273269810,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062368,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062368,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999920,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999920,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053648,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053648,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int vfs_fsync_range(struct file * file, loff_t start, loff_t end, int datasync)
```

```json
{
  "name": "vfs_fsync_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125328,
      "name": "vfs_fsync_range",
      "external": true,
      "loc": "fs/sync.c:190",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "fs/sync.c:do_fsync",
        "fs/direct-io.c:dio_complete",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125328,
      "name": "vfs_fsync_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
