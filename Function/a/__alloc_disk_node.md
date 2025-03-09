# Function: <code>__alloc_disk_node</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452592,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1388",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452592,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1409",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665764,
      "name": "__alloc_disk_node.cold.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583663856,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1434",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583772582,
      "name": "__alloc_disk_node.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583770688,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1455",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962436,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583960272,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065803,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584063744,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1676",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463066,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584460736,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1571",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591373053,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584576080,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1277",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315607,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584606336,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
struct gendisk * __alloc_disk_node(struct request_queue * q, int node_id, struct lock_class_key * lkclass)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585021328,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1277",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/genhd.c:__blk_alloc_disk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585021328,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct gendisk * __alloc_disk_node(struct request_queue * q, int node_id, struct lock_class_key * lkclass)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738848,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1336",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/genhd.c:__blk_alloc_disk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738848,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
struct gendisk * __alloc_disk_node(struct request_queue * q, int node_id, struct lock_class_key * lkclass)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586523104,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1359",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/genhd.c:__blk_alloc_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523104,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
struct gendisk * __alloc_disk_node(struct request_queue * q, int node_id, struct lock_class_key * lkclass)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586769312,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1322",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/genhd.c:__blk_alloc_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769312,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
struct gendisk * __alloc_disk_node(struct request_queue * q, int node_id, struct lock_class_key * lkclass)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587041888,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1335",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_disk_for_queue",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/genhd.c:__blk_alloc_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587041888,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495905888,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495905888,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229248796,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229248796,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290114016,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290114016,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275021024,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275021024,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034539,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584032480,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_add",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/blk.c:nd_blk_probe",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970303,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583968272,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018299,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584016240,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct gendisk * __alloc_disk_node(int minors, int node_id)
```

```json
{
  "name": "__alloc_disk_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_disk_node",
      "external": true,
      "loc": "block/genhd.c:1464",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120845,
      "name": "__alloc_disk_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584118800,
      "name": "__alloc_disk_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
struct gendisk * __alloc_disk_node(int minors, int node_id)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param added. </b>
<code>struct lock_class_key * lkclass</code>
</li>
<li>
<b>Param removed. </b>
<code>int minors</code>
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
