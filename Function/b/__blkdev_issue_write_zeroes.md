# Function: <code>__blkdev_issue_write_zeroes</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583173138,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:240",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_zeroout"
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
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583230338,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:224",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_zeroout"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406288,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:225",
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
      "addr": 18446744071583406288,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583616784,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:247",
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
      "addr": 18446744071583616784,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722080,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446744071583722080,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583910272,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446744071583910272,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584013440,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446744071584013440,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584405344,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446744071584405344,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520416,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:246",
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
      "addr": 18446744071584520416,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553024,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:246",
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
      "addr": 18446744071584553024,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964432,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:247",
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
      "addr": 18446744071584964432,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:120",
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
      "addr": 18446744071585668592,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    },
    {
      "addr": 18446744071594096272,
      "name": "__blkdev_issue_write_zeroes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:118",
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
      "addr": 18446744071586444336,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071596105257,
      "name": "__blkdev_issue_write_zeroes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:118",
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
      "addr": 18446744071586691456,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071596629269,
      "name": "__blkdev_issue_write_zeroes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:118",
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
      "addr": 18446744071586962800,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071597535775,
      "name": "__blkdev_issue_write_zeroes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495843376,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446603336495843376,
      "name": "__blkdev_issue_write_zeroes",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229191488,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 3229191488,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290036336,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 13835058055290036336,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274973570,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446743936274973570,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982176,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446744071583982176,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918032,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446744071583918032,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583965936,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446744071583965936,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_write_zeroes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067984,
      "name": "__blkdev_issue_write_zeroes",
      "external": false,
      "loc": "block/blk-lib.c:212",
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
      "addr": 18446744071584067984,
      "name": "__blkdev_issue_write_zeroes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int __blkdev_issue_write_zeroes(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
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
