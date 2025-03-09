# Function: <code>file_write_and_wait_range</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580655696,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:645",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655696,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736048,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:747",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync_common",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736048,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874080,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:747",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync_common",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874080,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947296,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:724",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947296,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044560,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:767",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044560,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100080,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100080,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276096,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:754",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276096,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322976,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:755",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322976,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342560,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:786",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342560,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577264,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:804",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "block/fops.c:blkdev_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577264,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948096,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:773",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "block/fops.c:blkdev_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948096,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381936,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:768",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "block/fops.c:blkdev_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381936,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582608,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:775",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/buffer.c:generic_buffers_fsync_noflush",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "block/fops.c:blkdev_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582608,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753744,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:770",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/buffer.c:generic_buffers_fsync_noflush",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "block/fops.c:blkdev_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753744,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492465000,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492465000,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226340916,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226340916,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285746032,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285746032,
      "name": "file_write_and_wait_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272535776,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272535776,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068928,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068928,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016128,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016128,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060128,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060128,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
```

```json
{
  "name": "file_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121712,
      "name": "file_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:776",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fuse/file.c:fuse_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121712,
      "name": "file_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int file_write_and_wait_range(struct file * file, loff_t lstart, loff_t lend)
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
