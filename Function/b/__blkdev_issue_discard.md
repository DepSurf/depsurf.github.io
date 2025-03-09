# Function: <code>__blkdev_issue_discard</code>

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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583064784,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583064784,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583171936,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583171936,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229200,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229200,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583405840,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:26",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583405840,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583616128,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:26",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616128,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720880,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720880,
      "name": "__blkdev_issue_discard",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583909056,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909056,
      "name": "__blkdev_issue_discard",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012256,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012256,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404704,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404704,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372680,
      "name": "__blkdev_issue_discard.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584521472,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315279,
      "name": "__blkdev_issue_discard.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584554096,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:26",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_discard",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592313434,
      "name": "__blkdev_issue_discard.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584965504,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:38",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_discard",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594096203,
      "name": "__blkdev_issue_discard.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071585667856,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:38",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_discard",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596105209,
      "name": "__blkdev_issue_discard.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586443616,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:38",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_discard",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596629221,
      "name": "__blkdev_issue_discard.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586690768,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:38",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_discard",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597535727,
      "name": "__blkdev_issue_discard.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586962112,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495842280,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495842280,
      "name": "__blkdev_issue_discard",
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229190204,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229190204,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290034800,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290034800,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274972666,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274972666,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980992,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980992,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916848,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916848,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964752,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964752,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584066832,
      "name": "__blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:25",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-lib.c:blkdev_issue_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584066832,
      "name": "__blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
int __blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, int flags, struct bio * * biop)
```
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, sector, nr_sects, gfp_mask, flags, biop</code> ➡️ <code>bdev, sector, nr_sects, gfp_mask, biop</code>
</li>
</ul>
</details>
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
