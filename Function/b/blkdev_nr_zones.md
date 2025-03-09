# Function: <code>blkdev_nr_zones</code>

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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873664,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:85",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873664,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584065312,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065312,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584188032,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188032,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int blkdev_nr_zones(struct gendisk * disk)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581312,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:126",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_common_ioctl",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581312,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
unsigned int blkdev_nr_zones(struct gendisk * disk)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698544,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:126",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_common_ioctl",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698544,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int blkdev_nr_zones(struct gendisk * disk)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584726640,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:118",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_common_ioctl",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726640,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
unsigned int blkdev_nr_zones(struct gendisk * disk)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:118",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_common_ioctl",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592321817,
      "name": "blkdev_nr_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071585153616,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
unsigned int blkdev_nr_zones(struct gendisk * disk)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:117",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_common_ioctl",
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594106496,
      "name": "blkdev_nr_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585888576,
      "name": "blkdev_nr_zones",
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496054240,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496054240,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229383504,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229383504,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290287872,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290287872,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275130436,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275130436,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156768,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156768,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584092032,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092032,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140528,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140528,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```

```json
{
  "name": "blkdev_nr_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244688,
      "name": "blkdev_nr_zones",
      "external": true,
      "loc": "block/blk-zoned.c:89",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkdev_ioctl",
        "block/blk-zoned.c:blkdev_report_zones_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244688,
      "name": "blkdev_nr_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int blkdev_nr_zones(struct block_device * bdev)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<code>struct gendisk * disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device * bdev</code>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int blkdev_nr_zones(struct gendisk * disk)
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
