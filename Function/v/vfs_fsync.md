# Function: <code>vfs_fsync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581206080,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:207",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206080,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581370822,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:207",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370752,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581448678,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:208",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448608,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581502838,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:208",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502768,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581644982,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:209",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644912,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581803766,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803696,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581890774,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890704,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582015878,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015808,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582093830,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093760,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582330835,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:213",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330944,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582382259,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:213",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382368,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410018,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:212",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410128,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582731410,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:213",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582731520,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583277654,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:200",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583277776,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583860310,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:200",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860448,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584082054,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:200",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082192,
      "name": "vfs_fsync",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584298118,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:200",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298256,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493629972,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493629856,
      "name": "vfs_fsync",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227170192,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227170088,
      "name": "vfs_fsync",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287220300,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287220192,
      "name": "vfs_fsync",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273270020,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273269914,
      "name": "vfs_fsync",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582062566,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062496,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582000118,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000048,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582053846,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053776,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int vfs_fsync(struct file * file, int datasync)
```

```json
{
  "name": "vfs_fsync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582125526,
      "name": "vfs_fsync",
      "external": true,
      "loc": "fs/sync.c:210",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:do_fsync"
      ],
      "caller_func": [
        "fs/aio.c:aio_fsync_work",
        "fs/iomap/swapfile.c:iomap_swapfile_activate",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125456,
      "name": "vfs_fsync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
