# Function: <code>blk_mq_requeue_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_requeue_request(struct request * rq)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582791600,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:448",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/md/dm.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791600,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void blk_mq_requeue_request(struct request * rq)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583069392,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:504",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069392,
      "name": "blk_mq_requeue_request",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583177328,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:525",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177328,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583236464,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:612",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236464,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583417376,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:665",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417376,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583627360,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:680",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627360,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583730880,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:716",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730880,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583922208,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:716",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922208,
      "name": "blk_mq_requeue_request",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584025504,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025504,
      "name": "blk_mq_requeue_request",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584423328,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:728",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584423328,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584538320,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:778",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538320,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584569776,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:752",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569776,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584980688,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:759",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980688,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585691952,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:1309",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691952,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586471088,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:1437",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586471088,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586705872,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:1445",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/virtio_blk.c:virtio_queue_rqs",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705872,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586975984,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:1448",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/virtio_blk.c:virtio_queue_rqs",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975984,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495857648,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495857648,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229204832,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229204832,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290054496,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290054496,
      "name": "blk_mq_requeue_request",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274984898,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274984898,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583994240,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/nvme/host/core.c:nvme_complete_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994240,
      "name": "blk_mq_requeue_request",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583930096,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/nvme/host/core.c:nvme_complete_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930096,
      "name": "blk_mq_requeue_request",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583978000,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978000,
      "name": "blk_mq_requeue_request",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_requeue_request(struct request * rq, bool kick_requeue_list)
```

```json
{
  "name": "blk_mq_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584080240,
      "name": "blk_mq_requeue_request",
      "external": true,
      "loc": "block/blk-mq.c:729",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584080240,
      "name": "blk_mq_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool kick_requeue_list</code>
</li>
</ul>
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
