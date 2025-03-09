# Function: <code>__blkdev_issue_zero_pages</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407248,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:278",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407248,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583617840,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:303",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617840,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722416,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722416,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583910608,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583910608,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584013776,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013776,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404272,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404272,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584519984,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:302",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519984,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584552608,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:302",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552608,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964016,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:303",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964016,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:170",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668912,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    },
    {
      "addr": 18446744071594096338,
      "name": "__blkdev_issue_zero_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:168",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444672,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    },
    {
      "addr": 18446744071596105323,
      "name": "__blkdev_issue_zero_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:168",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691792,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071596629335,
      "name": "__blkdev_issue_zero_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:168",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963136,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071597535841,
      "name": "__blkdev_issue_zero_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495843752,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495843752,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229191888,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229191888,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290036896,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290036896,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274973872,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274973872,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982512,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982512,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918368,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918368,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583966272,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966272,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```

```json
{
  "name": "__blkdev_issue_zero_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068304,
      "name": "__blkdev_issue_zero_pages",
      "external": false,
      "loc": "block/blk-lib.c:268",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:__blkdev_issue_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068304,
      "name": "__blkdev_issue_zero_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __blkdev_issue_zero_pages(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop)
```
</details>
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
