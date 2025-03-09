# Function: <code>bio_check_pages_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723376,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1645",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723376,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999776,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1644",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999776,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583104704,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1699",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583104704,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160384,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1705",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160384,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583336144,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1669",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583336144,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583545360,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1725",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545360,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668720,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1642",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668720,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857312,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1691",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857312,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583959968,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959968,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348672,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1359",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348672,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465440,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1362",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465440,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584500416,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1326",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584500416,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584910912,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1408",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910912,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585611472,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1467",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611472,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586380608,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1530",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380608,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626960,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1515",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626960,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586891316,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1522",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597534576,
      "name": "bio_check_pages_dirty.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586891008,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495781560,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495781560,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229133556,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229133556,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289958256,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289958256,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274925456,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274925456,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928704,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928704,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583865648,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865648,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912464,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912464,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void bio_check_pages_dirty(struct bio * bio)
```

```json
{
  "name": "bio_check_pages_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584013760,
      "name": "bio_check_pages_dirty",
      "external": true,
      "loc": "block/bio.c:1733",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013760,
      "name": "bio_check_pages_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
