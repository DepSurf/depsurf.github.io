# Function: <code>del_gendisk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582824416,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:637",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/block/brd.c:brd_exit",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_release_gendisk",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824416,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103648,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:639",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_exit",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103648,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215152,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:639",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215152,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583273024,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:640",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583273024,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453216,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:698",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453216,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664480,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:727",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664480,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 691
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583771312,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:749",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583771312,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:764",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962464,
      "name": "del_gendisk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583960944,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584064416,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064416,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584461648,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:880",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584461648,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584576896,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:811",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584576896,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584609136,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:600",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584609136,
      "name": "del_gendisk",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585023040,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:581",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585023040,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738096,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:596",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738096,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586519904,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:590",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519904,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766592,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:630",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766592,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 919
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039072,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:641",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039072,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495906680,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_blk_remove_req",
        "drivers/mmc/core/block.c:mmc_blk_remove_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495906680,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229249480,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_blk_remove_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229249480,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290114976,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290114976,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275021642,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/block.c:mmc_add_disk",
        "drivers/mmc/core/block.c:mmc_blk_remove_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275021642,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033152,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033152,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968944,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/nvdimm/pmem.c:pmem_release_disk",
        "drivers/nvdimm/btt.c:nvdimm_namespace_detach_btt",
        "drivers/nvdimm/blk.c:nd_blk_release_disk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968944,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016912,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016912,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
void del_gendisk(struct gendisk * disk)
```

```json
{
  "name": "del_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584119472,
      "name": "del_gendisk",
      "external": true,
      "loc": "block/genhd.c:773",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584119472,
      "name": "del_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
