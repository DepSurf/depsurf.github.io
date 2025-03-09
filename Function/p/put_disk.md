# Function: <code>put_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582818384,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1326",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/block/brd.c:brd_free",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_release_gendisk",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582818384,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097536,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1355",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "drivers/block/brd.c:brd_free",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097536,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583209040,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1355",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583209040,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583267216,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1378",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583267216,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583448222,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1462",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446944,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583660137,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1483",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658416,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583766409,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1508",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764688,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583955749,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1529",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953648,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584059221,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057120,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584460487,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1751",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453168,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584571008,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1623",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_put",
        "fs/block_dev.c:blkdev_get_no_open",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571008,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601184,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1327",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_put",
        "fs/block_dev.c:blkdev_get_no_open",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601184,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585019526,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1358",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_cleanup_disk"
      ],
      "caller_func": [
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:part_release",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015984,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585737414,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1424",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_cleanup_disk",
        "block/genhd.c:blk_cleanup_disk"
      ],
      "caller_func": [
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:part_release",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737664,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586516784,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1450",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:part_release",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586516784,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586764032,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1413",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:part_release",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764032,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587036512,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1426",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:part_release",
        "block/blk-cgroup.c:blkcg_schedule_throttle",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_remove",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036512,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495899864,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/mmc/core/block.c:mmc_blk_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495897360,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229242524,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/mtd/mtd_blkdevs.c:blktrans_dev_release",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/mmc/core/block.c:mmc_blk_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229240800,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290107160,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290103632,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275016370,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/mmc/core/block.c:mmc_blk_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275014356,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584027957,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_free_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025856,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583963765,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/pmem.c:pmem_release_disk",
        "drivers/nvdimm/btt.c:nvdimm_namespace_detach_btt",
        "drivers/nvdimm/blk.c:nd_blk_release_disk",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/nvme/host/core.c:nvme_free_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961664,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584011717,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584009616,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk(struct gendisk * disk)
```

```json
{
  "name": "put_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584114645,
      "name": "put_disk",
      "external": true,
      "loc": "block/genhd.c:1538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112128,
      "name": "put_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
