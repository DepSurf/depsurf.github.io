# Function: <code>blk_mq_unquiesce_queue</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583239424,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:202",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_start_queue",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239424,
      "name": "blk_mq_unquiesce_queue",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583413216,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:241",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_start_queue",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413216,
      "name": "blk_mq_unquiesce_queue",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583640203,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:252",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "drivers/scsi/scsi_lib.c:scsi_start_queue",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583623248,
      "name": "blk_mq_unquiesce_queue",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583746445,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:256",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728080,
      "name": "blk_mq_unquiesce_queue",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583935590,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:259",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919648,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584038950,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584022944,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584433755,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:245",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416976,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584550271,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:249",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532720,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584582898,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:249",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564336,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584997003,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:256",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584975136,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681712,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:294",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/genhd.c:del_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681712,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586459856,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:298",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_unquiesce_tagset",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459856,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586703120,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:257",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_unquiesce_tagset",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/virtio_blk.c:virtblk_restore",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703120,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586975152,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:257",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_unquiesce_tagset",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975152,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495872168,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/mmc/core/queue.c:mmc_queue_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495853872,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229219280,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev",
        "drivers/md/dm-rq.c:dm_start_queue",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/mmc/core/queue.c:mmc_queue_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229203016,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290073668,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290051872,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274996860,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/mmc/core/queue.c:mmc_queue_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274982170,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584007686,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/nvme/host/core.c:nvme_start_queues",
        "drivers/nvme/host/core.c:nvme_kill_queues",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/nvme/host/pci.c:nvme_dev_remove_admin",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991680,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583943510,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/nvme/host/core.c:nvme_start_queues",
        "drivers/nvme/host/core.c:nvme_kill_queues",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/nvme/host/pci.c:nvme_dev_remove_admin",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927536,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583991446,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975440,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_mq_unquiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_unquiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584093750,
      "name": "blk_mq_unquiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074864,
      "name": "blk_mq_unquiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void blk_mq_unquiesce_queue(struct request_queue * q)
```
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
