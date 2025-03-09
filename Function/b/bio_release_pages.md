# Function: <code>bio_release_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582723657,
      "name": "bio_release_pages",
      "external": false,
      "loc": "block/bio.c:1592",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583000159,
      "name": "bio_release_pages",
      "external": false,
      "loc": "block/bio.c:1591",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583105087,
      "name": "bio_release_pages",
      "external": false,
      "loc": "block/bio.c:1646",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583160702,
      "name": "bio_release_pages",
      "external": false,
      "loc": "block/bio.c:1652",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583336510,
      "name": "bio_release_pages",
      "external": false,
      "loc": "block/bio.c:1616",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583545740,
      "name": "bio_release_pages",
      "external": false,
      "loc": "block/bio.c:1672",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583668578,
      "name": "bio_release_pages",
      "external": false,
      "loc": "block/bio.c:1595",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583857334,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:836",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849936,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071583853824,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959990,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952848,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071583955824,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584348696,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:947",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/blk-map.c:__blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342752,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071584343024,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584465464,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:947",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584461280,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071584461536,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584500440,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:936",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495920,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071584496176,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584910936,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584903904,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071584904160,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583337853,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:dio_bio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583619461,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585594561,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585611527,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655757,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583920554,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:dio_bio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584223557,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586361745,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586380663,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586429780,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:485",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584154053,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:493",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:dio_bio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584452984,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:493",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586609624,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:493",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586626981,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:493",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586677396,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:493",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_release_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584368245,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:508",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:dio_bio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584676032,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:508",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586879032,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:508",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586891521,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:508",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586948724,
      "name": "bio_release_pages",
      "external": false,
      "loc": "include/linux/bio.h:508",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495781592,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495772248,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446603336495777504,
      "name": "bio_release_pages",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229133592,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229125964,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 3229129496,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289958296,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289948736,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 13835058055289952288,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274925488,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274919156,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446743936274922156,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583928726,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921584,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071583924560,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583865670,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858544,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071583861504,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583912486,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905344,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071583908320,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584013782,
      "name": "bio_release_pages",
      "external": true,
      "loc": "block/bio.c:875",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006608,
      "name": "bio_release_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071584009616,
      "name": "bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void bio_release_pages(struct bio * bio, bool mark_dirty)
```
</details>
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
void bio_release_pages(struct bio * bio, bool mark_dirty)
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
