# Function: <code>do_blockdev_direct_IO</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, loff_t offset, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581245600,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1108",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581245600,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13322
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412240,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1117",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412240,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12316
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492880,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1107",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492880,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12874
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547792,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1110",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547792,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10460
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690992,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1150",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690992,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11170
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581857392,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1171",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857392,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11450
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942128,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1172",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942128,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11774
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083216,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1165",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083216,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3264
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582160656,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160656,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3262
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582397680,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1145",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397680,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3082
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451488,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1126",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451488,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2267
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478336,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1129",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478336,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1129",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791120,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2666
    },
    {
      "addr": 18446744071592234462,
      "name": "do_blockdev_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    }
  ]
}
```
</details>
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493714280,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493714280,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3084
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227241008,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227241008,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3212
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287320080,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287320080,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3548
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273327938,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273327938,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2260
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129392,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129392,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3262
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066832,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066832,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3262
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582119872,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582119872,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3262
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
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
```

```json
{
  "name": "do_blockdev_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582192864,
      "name": "do_blockdev_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:1164",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192864,
      "name": "do_blockdev_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3262
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
ssize_t do_blockdev_direct_IO(struct kiocb * iocb, struct inode * inode, struct block_device * bdev, struct iov_iter * iter, get_block_t * get_block, dio_iodone_t * end_io, dio_submit_t * submit_io, int flags)
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
