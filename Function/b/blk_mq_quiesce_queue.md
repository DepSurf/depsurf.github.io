# Function: <code>blk_mq_quiesce_queue</code>

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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583175376,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:128",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175376,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231968,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:176",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231968,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583409264,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:215",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409264,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619840,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:226",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619840,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583724432,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:230",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724432,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912752,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:233",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912752,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584015888,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584015888,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584408192,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:219",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408192,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524048,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:223",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524048,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584556624,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:223",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556624,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584967808,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:230",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967808,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585708892,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:280",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/genhd.c:del_gendisk",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683920,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586488892,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:282",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586461632,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586736447,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:241",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705200,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587008540,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:241",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_nr_requests"
      ],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586979056,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495846064,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue",
        "drivers/mmc/core/queue.c:mmc_queue_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495846064,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229194176,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev",
        "drivers/md/dm-rq.c:dm_stop_queue",
        "drivers/mmc/core/queue.c:mmc_queue_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229194176,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290040320,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290040320,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274975802,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue",
        "drivers/mmc/core/queue.c:mmc_queue_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274975802,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583984624,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/nvme/host/core.c:nvme_stop_queues",
        "drivers/nvme/host/pci.c:nvme_suspend_queue",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984624,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583920480,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/nvme/host/core.c:nvme_stop_queues",
        "drivers/nvme/host/pci.c:nvme_suspend_queue",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920480,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968384,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968384,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_quiesce_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070400,
      "name": "blk_mq_quiesce_queue",
      "external": true,
      "loc": "block/blk-mq.c:234",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/scsi/scsi_lib.c:device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070400,
      "name": "blk_mq_quiesce_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_quiesce_queue(struct request_queue * q)
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
