# Function: <code>device_add_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void device_add_disk(struct device * parent, struct gendisk * disk)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101568,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:585",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_init",
        "drivers/block/brd.c:brd_probe",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_probe_async",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101568,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1153
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
void device_add_disk(struct device * parent, struct gendisk * disk)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213088,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:585",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe_async",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213088,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1147
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
void device_add_disk(struct device * parent, struct gendisk * disk)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583271104,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:586",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_probe_async",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271104,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
void device_add_disk(struct device * parent, struct gendisk * disk)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583451216,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:641",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_probe_async",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451216,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1088
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
void device_add_disk(struct device * parent, struct gendisk * disk)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663504,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:715",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_probe_async",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663504,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583770336,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:735",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_probe_async",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770336,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583959888,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:750",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959888,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584063360,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063360,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584459936,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:847",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459936,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584575456,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:766",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575456,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584608144,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:567",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608144,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:393",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592315085,
      "name": "device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585020368,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 945
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
int device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:410",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594099679,
      "name": "device_add_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585739888,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
int device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586521392,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:390",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521392,
      "name": "device_add_disk",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586767536,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:396",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767536,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
int device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587040048,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:396",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040048,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1045
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495905360,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/mmc/core/block.c:mmc_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495905360,
      "name": "device_add_disk",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229248384,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/md/md.c:md_alloc",
        "drivers/mmc/core/block.c:mmc_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229248384,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290113472,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290113472,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275020572,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/mmc/core/block.c:mmc_add_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275020572,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584032096,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584032096,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583967888,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/blk.c:nd_blk_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967888,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584015856,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584015856,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void device_add_disk(struct device * parent, struct gendisk * disk, const struct attribute_group * * groups)
```

```json
{
  "name": "device_add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584118416,
      "name": "device_add_disk",
      "external": true,
      "loc": "block/genhd.c:759",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118416,
      "name": "device_add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void device_add_disk(struct device * parent, struct gendisk * disk)
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct attribute_group * * groups</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
