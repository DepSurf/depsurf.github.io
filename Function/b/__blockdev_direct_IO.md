# Function: <code>__blockdev_direct_IO</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, loff_t offset, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258928,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1323",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258928,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424560,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1338",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424560,
      "name": "__blockdev_direct_IO",
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505760,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1328",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505760,
      "name": "__blockdev_direct_IO",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558256,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1333",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558256,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702176,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1381",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702176,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868848,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1399",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868848,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953904,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1402",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953904,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086480,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1395",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086480,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582163920,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582163920,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400768,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1375",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400768,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453760,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1347",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453760,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480832,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1350",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480832,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582793792,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1350",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793792,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1118",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594014673,
      "name": "__blockdev_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071583343440,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2855
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1122",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596054388,
      "name": "__blockdev_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071583926880,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2879
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1104",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596579228,
      "name": "__blockdev_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
    },
    {
      "addr": 18446744071584160064,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2507
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1104",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597483271,
      "name": "__blockdev_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    },
    {
      "addr": 18446744071584374240,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2526
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493717368,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493717368,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227244220,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227244220,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287323632,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287323632,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273330198,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273330198,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132656,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132656,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070096,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070096,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123136,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123136,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
ssize_t __blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "__blockdev_direct_IO",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196128,
      "name": "__blockdev_direct_IO",
      "external": true,
      "loc": "fs/direct-io.c:1394",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/fat/inode.c:fat_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196128,
      "name": "__blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocb, inode, bdev, iter, offset, get_block, end_io, submit_io, flags</code> ➡️ <code>iocb, inode, bdev, iter, get_block, end_io, submit_io, flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>dio_submit_t * submit_io</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocb, inode, bdev, iter, get_block, end_io, submit_io, flags</code> ➡️ <code>iocb, inode, bdev, iter, get_block, end_io, flags</code>
</li>
</ul>
</details>
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
