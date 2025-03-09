# Function: <code>__blkdev_issue_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582788329,
      "name": "__blkdev_issue_zeroout",
      "external": false,
      "loc": "block/blk-lib.c:215",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_zeroout"
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
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583065902,
      "name": "__blkdev_issue_zeroout",
      "external": false,
      "loc": "block/blk-lib.c:199",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:blkdev_issue_zeroout"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, bool discard)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583173088,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:290",
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
      "addr": 18446744071583173088,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583230288,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:302",
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
      "addr": 18446744071583230288,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583408144,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:331",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408144,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583618240,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:359",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583618240,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722832,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722832,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583911008,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583911008,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014176,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014176,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584405728,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405728,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520800,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520800,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553392,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553392,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964800,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:359",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964800,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669296,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:220",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669296,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586445088,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:218",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586445088,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586692192,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:218",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586692192,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586963536,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:218",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963536,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495844144,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495844144,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229192260,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229192260,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290037392,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290037392,
      "name": "__blkdev_issue_zeroout",
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274974220,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274974220,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982912,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982912,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918768,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918768,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583966672,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966672,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, unsigned int flags)
```

```json
{
  "name": "__blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068688,
      "name": "__blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:324",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068688,
      "name": "__blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, struct bio * * biop, bool discard)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool discard</code>
</li>
</ul>
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
