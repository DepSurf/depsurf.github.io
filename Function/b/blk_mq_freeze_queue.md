# Function: <code>blk_mq_freeze_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582797536,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:115",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797536,
      "name": "blk_mq_freeze_queue",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583077982,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:115",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_switch",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076528,
      "name": "blk_mq_freeze_queue",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583187038,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:97",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185520,
      "name": "blk_mq_freeze_queue",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583248461,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:130",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:loop_switch",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239280,
      "name": "blk_mq_freeze_queue",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583427592,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:169",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417968,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583638871,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:184",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629216,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583744274,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:188",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728304,
      "name": "blk_mq_freeze_queue",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583933256,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:191",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919456,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584036616,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584022752,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584431242,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:177",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417216,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584547658,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:181",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_shared"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532960,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584580266,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:181",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_shared"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-zoned.c:blk_queue_clear_zone_settings",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-wbt.c:wbt_init",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564128,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584994186,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:181",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-ioprio.c:blk_ioprio_init",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-zoned.c:blk_queue_clear_zone_settings",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-wbt.c:wbt_init",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584975088,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585705783,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:210",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-ioprio.c:blk_ioprio_init",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-zoned.c:blk_queue_clear_zone_settings",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-wbt.c:wbt_init",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681664,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586483927,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:210",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-zoned.c:disk_clear_zone_settings",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-wbt.c:wbt_init",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459792,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586731511,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:169",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-rq-qos.c:rq_qos_del",
        "block/blk-rq-qos.c:rq_qos_add",
        "block/blk-cgroup.c:blkcg_deactivate_policy",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-zoned.c:disk_clear_zone_settings",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703056,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587003453,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:169",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-rq-qos.c:rq_qos_del",
        "block/blk-rq-qos.c:rq_qos_add",
        "block/blk-cgroup.c:blkcg_deactivate_policy",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975088,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495869792,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495853648,
      "name": "blk_mq_freeze_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229216852,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229202820,
      "name": "blk_mq_freeze_queue",
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290070528,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290051536,
      "name": "blk_mq_freeze_queue",
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274994980,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274981968,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584005352,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/nvme/host/core.c:nvme_update_disk_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991488,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583941176,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/nvme/host/core.c:nvme_update_disk_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927344,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583989112,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975248,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void blk_mq_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_mq_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584091416,
      "name": "blk_mq_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:192",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_init_mq",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "block/blk-zoned.c:blk_revalidate_disk_zones",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/scsi/sd.c:scsi_disk_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074672,
      "name": "blk_mq_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
