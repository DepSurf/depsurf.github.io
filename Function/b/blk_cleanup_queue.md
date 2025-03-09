# Function: <code>blk_cleanup_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582747600,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:542",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/block/brd.c:brd_free",
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_release_gendisk",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747600,
      "name": "blk_cleanup_queue",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583025600,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:544",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/block/brd.c:brd_free",
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025600,
      "name": "blk_cleanup_queue",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130464,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:545",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130464,
      "name": "blk_cleanup_queue",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583185472,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:623",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/scsi_lib.c:scsi_alloc_queue",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185472,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363552,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:666",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363552,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575168,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:754",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575168,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583688544,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:329",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688544,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872352,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:334",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872352,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583975248,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975248,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584362704,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:356",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_sq_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584362704,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479520,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:371",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_sq_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479520,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584514144,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:372",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_sq_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584514144,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584927280,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:362",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:blk_mq_init_queue",
        "block/genhd.c:blk_cleanup_disk",
        "block/genhd.c:__blk_alloc_disk",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584927280,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585629456,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:296",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:__blk_mq_alloc_disk",
        "block/blk-mq.c:blk_mq_init_queue",
        "block/genhd.c:blk_cleanup_disk",
        "block/genhd.c:__blk_alloc_disk",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629456,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495795832,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495795832,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229148064,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/mtd/mtd_blkdevs.c:blktrans_dev_release",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229148064,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289979440,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289979440,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274937420,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274937420,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583943984,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/nvme/host/pci.c:nvme_dev_remove_admin",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943984,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880928,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/nvdimm/pmem.c:pmem_release_queue",
        "drivers/nvdimm/btt.c:nvdimm_namespace_detach_btt",
        "drivers/nvdimm/blk.c:nd_blk_probe",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_remove_disk",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/nvme/host/pci.c:nvme_dev_remove_admin",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880928,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927744,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927744,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_cleanup_queue(struct request_queue * q)
```

```json
{
  "name": "blk_cleanup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584029136,
      "name": "blk_cleanup_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/lightnvm/core.c:__nvm_remove_target",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_sysfs.c:__scsi_remove_device",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029136,
      "name": "blk_cleanup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void blk_cleanup_queue(struct request_queue * q)
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
