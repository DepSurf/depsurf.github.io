# Function: <code>blk_mq_start_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789776,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:396",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789776,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067312,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:452",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067312,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583174848,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:466",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583174848,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234368,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:545",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234368,
      "name": "blk_mq_start_request",
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583411904,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:587",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411904,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620848,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:630",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620848,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725440,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:666",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725440,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913952,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:668",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913952,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017088,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017088,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584414672,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:688",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_prep_fn",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584414672,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584530448,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:738",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584530448,
      "name": "blk_mq_start_request",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584561296,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:712",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561296,
      "name": "blk_mq_start_request",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972432,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:719",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972432,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585682464,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:1130",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585682464,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586460192,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:1249",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586460192,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586703456,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:1248",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703456,
      "name": "blk_mq_start_request",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586976448,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:1249",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976448,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495851912,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/mmc/core/queue.c:mmc_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495851912,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229195432,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/mtd/mtd_blkdevs.c:mtd_queue_rq",
        "drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/mmc/core/queue.c:mmc_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229195432,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290042192,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290042192,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274976898,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/mmc/core/queue.c:mmc_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274976898,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583985824,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/nvme/host/pci.c:nvme_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985824,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921680,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/nvme/host/pci.c:nvme_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921680,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583969584,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969584,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void blk_mq_start_request(struct request * rq)
```

```json
{
  "name": "blk_mq_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071616,
      "name": "blk_mq_start_request",
      "external": true,
      "loc": "block/blk-mq.c:678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_queue_rq",
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071616,
      "name": "blk_mq_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
