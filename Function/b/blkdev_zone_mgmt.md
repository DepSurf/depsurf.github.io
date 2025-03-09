# Function: <code>blkdev_zone_mgmt</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int blkdev_zone_mgmt(struct block_device * bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_zone_mgmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581488,
      "name": "blkdev_zone_mgmt",
      "external": true,
      "loc": "block/blk-zoned.c:202",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581488,
      "name": "blkdev_zone_mgmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int blkdev_zone_mgmt(struct block_device * bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_zone_mgmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698992,
      "name": "blkdev_zone_mgmt",
      "external": true,
      "loc": "block/blk-zoned.c:202",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698992,
      "name": "blkdev_zone_mgmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int blkdev_zone_mgmt(struct block_device * bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_zone_mgmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584727072,
      "name": "blkdev_zone_mgmt",
      "external": true,
      "loc": "block/blk-zoned.c:194",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727072,
      "name": "blkdev_zone_mgmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int blkdev_zone_mgmt(struct block_device * bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_zone_mgmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585154640,
      "name": "blkdev_zone_mgmt",
      "external": true,
      "loc": "block/blk-zoned.c:265",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154640,
      "name": "blkdev_zone_mgmt",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int blkdev_zone_mgmt(struct block_device * bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_zone_mgmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_zone_mgmt",
      "external": true,
      "loc": "block/blk-zoned.c:260",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594106627,
      "name": "blkdev_zone_mgmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585889712,
      "name": "blkdev_zone_mgmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int blkdev_zone_mgmt(struct block_device * bdev, enum req_op op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_zone_mgmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_zone_mgmt",
      "external": true,
      "loc": "block/blk-zoned.c:256",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110480,
      "name": "blkdev_zone_mgmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071586677696,
      "name": "blkdev_zone_mgmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int blkdev_zone_mgmt(struct block_device * bdev, enum req_op op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_zone_mgmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_zone_mgmt",
      "external": true,
      "loc": "block/blk-zoned.c:250",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596634824,
      "name": "blkdev_zone_mgmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586937968,
      "name": "blkdev_zone_mgmt",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int blkdev_zone_mgmt(struct block_device * bdev, enum req_op op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_zone_mgmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_zone_mgmt",
      "external": true,
      "loc": "block/blk-zoned.c:250",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl",
        "block/blk-zoned.c:blkdev_zone_mgmt_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597542437,
      "name": "blkdev_zone_mgmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071587220384,
      "name": "blkdev_zone_mgmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int blkdev_zone_mgmt(struct block_device * bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask)
```
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum req_opf op</code> ➡️ <code>enum req_op op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
