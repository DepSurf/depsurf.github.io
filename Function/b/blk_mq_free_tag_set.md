# Function: <code>blk_mq_free_tag_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792352,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:2310",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_release_gendisk",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792352,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069648,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:2368",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069648,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583177840,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:2420",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177840,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583245744,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:2566",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245744,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424896,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:2733",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424896,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583636144,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:2795",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636144,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741168,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3076",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741168,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583930080,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3109",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930080,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584033440,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033440,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584427968,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3349",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_sq_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427968,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584544272,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3474",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_sq_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_init_blk_queue",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544272,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584576704,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3536",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_sq_queue",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_exit_cb",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_init_blk_queue",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584576704,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989728,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3584",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989728,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585702032,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:4335",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702032,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586481712,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:4547",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_free_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586481712,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586729280,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:4546",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_free_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729280,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587000912,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:4573",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_remove",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_free_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000912,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495866552,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495866552,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229213632,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/mtd/mtd_blkdevs.c:blktrans_dev_release",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229213632,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290066016,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290066016,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274992082,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/mmc/core/queue.c:mmc_cleanup_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274992082,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584002176,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_pci_free_ctrl",
        "drivers/nvme/host/pci.c:nvme_dev_remove_admin",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002176,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583938000,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_pci_free_ctrl",
        "drivers/nvme/host/pci.c:nvme_dev_remove_admin",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938000,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583985936,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985936,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void blk_mq_free_tag_set(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_free_tag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584088240,
      "name": "blk_mq_free_tag_set",
      "external": true,
      "loc": "block/blk-mq.c:3129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:scsi_mq_destroy_tags",
        "drivers/md/dm-rq.c:dm_mq_cleanup_mapped_device",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584088240,
      "name": "blk_mq_free_tag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
