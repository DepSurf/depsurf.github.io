# Function: <code>blkdev_report_zones</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583337312,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:65",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337312,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 997
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583396064,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:65",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583396064,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 933
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575488,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:65",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575488,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791680,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:107",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791680,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 927
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872752,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:159",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872752,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584063568,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063568,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186144,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186144,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581392,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:155",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581392,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698624,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:155",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698624,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584726720,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:147",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726720,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585153696,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:147",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-zone.c:dm_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153696,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585888672,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:146",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-zone.c:dm_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585888672,
      "name": "blkdev_report_zones",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int blkdev_report_zones(struct block_device * bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586675392,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:144",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-zone.c:dm_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586675392,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586936416,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:138",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-zone.c:dm_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586936416,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:138",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-zone.c:dm_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597542023,
      "name": "blkdev_report_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587217968,
      "name": "blkdev_report_zones",
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496051544,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496051544,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229380536,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229380536,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290285360,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290285360,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275128470,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275128470,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154880,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154880,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090144,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090144,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138640,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138640,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blkdev_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242800,
      "name": "blkdev_report_zones",
      "external": true,
      "loc": "block/blk-zoned.c:163",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_report_zones_ioctl",
        "drivers/md/dm-linear.c:linear_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242800,
      "name": "blkdev_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int blkdev_report_zones(struct block_device * bdev, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>report_zones_cb cb</code>
</li>
<li>
<b>Param added. </b>
<code>void * data</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_zone * zones</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, sector, zones, nr_zones</code> ➡️ <code>bdev, sector, nr_zones, cb, data</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int * nr_zones</code> ➡️ <code>unsigned int nr_zones</code>
</li>
</ul>
</details>
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
