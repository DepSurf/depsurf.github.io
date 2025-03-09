# Function: <code>blk_queue_max_discard_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582769232,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:280",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582769232,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047600,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:280",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047600,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153216,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:285",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153216,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210464,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:280",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210464,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387040,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:281",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387040,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583597072,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:281",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597072,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583703600,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:225",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703600,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892240,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:226",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892240,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995504,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995504,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384256,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:193",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384256,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498272,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:197",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498272,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532960,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:170",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532960,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584943872,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:173",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584943872,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585646544,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:172",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585646544,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586418720,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:172",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586418720,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666240,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:178",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666240,
      "name": "blk_queue_max_discard_sectors",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937264,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:177",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937264,
      "name": "blk_queue_max_discard_sectors",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495822728,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495822728,
      "name": "blk_queue_max_discard_sectors",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229172304,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229172304,
      "name": "blk_queue_max_discard_sectors",
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290011920,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290011920,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274957602,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274957602,
      "name": "blk_queue_max_discard_sectors",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964240,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/nvme/host/core.c:nvme_update_disk_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964240,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901152,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/nvme/host/core.c:nvme_update_disk_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901152,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583948000,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948000,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_queue_max_discard_sectors(struct request_queue * q, unsigned int max_discard_sectors)
```

```json
{
  "name": "blk_queue_max_discard_sectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049984,
      "name": "blk_queue_max_discard_sectors",
      "external": true,
      "loc": "block/blk-settings.c:227",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd.c:sd_config_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049984,
      "name": "blk_queue_max_discard_sectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
