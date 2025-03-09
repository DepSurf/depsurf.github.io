# Function: <code>blk_report_zones</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872480,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:118",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872480,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063312,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071584066302,
      "name": "blk_report_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584185888,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185888,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496051272,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496051272,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229380188,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229380188,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290284928,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290284928,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275128276,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275128276,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154624,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154624,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584089888,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089888,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138384,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138384,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "blk_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242544,
      "name": "blk_report_zones",
      "external": false,
      "loc": "block/blk-zoned.c:122",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blkdev_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242544,
      "name": "blk_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int blk_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
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
