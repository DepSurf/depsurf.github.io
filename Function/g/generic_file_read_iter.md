# Function: <code>generic_file_read_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478112,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:1756",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478112,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1457
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560528,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:1901",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560528,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2019
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625328,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2017",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625328,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2281
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580653136,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2145",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653136,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2549
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580740032,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2315",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740032,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3054
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878192,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2312",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878192,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945760,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2300",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945760,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581043072,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2294",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043072,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098544,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098544,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280800,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2276",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280800,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321552,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2587",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321552,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345568,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2650",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345568,
      "name": "generic_file_read_iter",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592928,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2731",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter",
        "block/fops.c:blkdev_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592928,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947712,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2784",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947712,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381552,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2791",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381552,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589328,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2798",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589328,
      "name": "generic_file_read_iter",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753312,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2745",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753312,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492463360,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492463360,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226339004,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226339004,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285743728,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285743728,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272534550,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272534550,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067392,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067392,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014592,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014592,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581058592,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058592,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
ssize_t generic_file_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "generic_file_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581120176,
      "name": "generic_file_read_iter",
      "external": true,
      "loc": "mm/filemap.c:2274",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ext4/file.c:ext4_file_read_iter",
        "fs/ecryptfs/file.c:ecryptfs_read_update_atime",
        "fs/fuse/file.c:fuse_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120176,
      "name": "generic_file_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
