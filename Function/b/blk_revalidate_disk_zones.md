# Function: <code>blk_revalidate_disk_zones</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:410",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875678,
      "name": "blk_revalidate_disk_zones.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071583873840,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1010
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:414",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584066321,
      "name": "blk_revalidate_disk_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584064464,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584187184,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187184,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int blk_revalidate_disk_zones(struct gendisk * disk, void (*)(struct gendisk *) update_driver_data)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:485",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584013,
      "name": "blk_revalidate_disk_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071584583472,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int blk_revalidate_disk_zones(struct gendisk * disk, void (*)(struct gendisk *) update_driver_data)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:520",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378512,
      "name": "blk_revalidate_disk_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071584700896,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
int blk_revalidate_disk_zones(struct gendisk * disk, void (*)(struct gendisk *) update_driver_data)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:512",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320754,
      "name": "blk_revalidate_disk_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071584728960,
      "name": "blk_revalidate_disk_zones",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int blk_revalidate_disk_zones(struct gendisk * disk, void (*)(struct gendisk *) update_driver_data)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:566",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592322204,
      "name": "blk_revalidate_disk_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585156656,
      "name": "blk_revalidate_disk_zones",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int blk_revalidate_disk_zones(struct gendisk * disk, void (*)(struct gendisk *) update_driver_data)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:559",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594106969,
      "name": "blk_revalidate_disk_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071585891840,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int blk_revalidate_disk_zones(struct gendisk * disk, void (*)(struct gendisk *) update_driver_data)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676640,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:554",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676640,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
int blk_revalidate_disk_zones(struct gendisk * disk, void (*)(struct gendisk *) update_driver_data)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:535",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_config_changed_work",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596634922,
      "name": "blk_revalidate_disk_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586938496,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int blk_revalidate_disk_zones(struct gendisk * disk, void (*)(struct gendisk *) update_driver_data)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:535",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597542193,
      "name": "blk_revalidate_disk_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071587218768,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496053456,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496053456,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229382612,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229382612,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 892
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290286784,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290286784,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1076
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275129454,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275129454,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584155920,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584155920,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584091184,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584091184,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139680,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139680,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int blk_revalidate_disk_zones(struct gendisk * disk)
```

```json
{
  "name": "blk_revalidate_disk_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243840,
      "name": "blk_revalidate_disk_zones",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243840,
      "name": "blk_revalidate_disk_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int blk_revalidate_disk_zones(struct gendisk * disk)
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
<code>void (*)(struct gendisk *) update_driver_data</code>
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
