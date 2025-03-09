# Function: <code>blk_mq_complete_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request * rq, int error)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582794240,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:377",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582794240,
      "name": "blk_mq_complete_request",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request * rq, int error)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583070496,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:433",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:dm_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070496,
      "name": "blk_mq_complete_request",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request * rq, int error)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583180112,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:447",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:dm_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583180112,
      "name": "blk_mq_complete_request",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234336,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:528",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:dm_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234336,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583411872,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:570",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:dm_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411872,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620576,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:616",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:dm_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620576,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725168,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:651",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725168,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913696,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:646",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913696,
      "name": "blk_mq_complete_request",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016832,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016832,
      "name": "blk_mq_complete_request",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417664,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417664,
      "name": "blk_mq_complete_request",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584531184,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:703",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531184,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584562896,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:677",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562896,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584973792,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:684",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973792,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684448,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:1115",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_done_internal",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585684448,
      "name": "blk_mq_complete_request",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586462224,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:1234",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_done_internal",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586462224,
      "name": "blk_mq_complete_request",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586707200,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:1233",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_done_internal",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586707200,
      "name": "blk_mq_complete_request",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586980320,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:1234",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_done_internal",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586980320,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495849000,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request",
        "drivers/mmc/core/block.c:mmc_blk_mq_post_req",
        "drivers/mmc/core/block.c:mmc_blk_cqe_req_done",
        "drivers/mmc/core/queue.c:mmc_mq_timed_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495849000,
      "name": "blk_mq_complete_request",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229195116,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request",
        "drivers/mmc/core/block.c:mmc_blk_mq_post_req",
        "drivers/mmc/core/block.c:mmc_blk_cqe_req_done",
        "drivers/mmc/core/queue.c:mmc_mq_timed_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229195116,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290041744,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290041744,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274976652,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request",
        "drivers/mmc/core/block.c:mmc_blk_mq_post_req",
        "drivers/mmc/core/block.c:mmc_blk_cqe_req_done",
        "drivers/mmc/core/queue.c:mmc_mq_timed_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274976652,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583985568,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/nvme/host/core.c:nvme_cancel_request",
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/nvme/host/pci.c:nvme_poll",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/nvme/host/pci.c:nvme_irq",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583985568,
      "name": "blk_mq_complete_request",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921424,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/nvme/host/core.c:nvme_cancel_request",
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/nvme/host/pci.c:nvme_poll",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/nvme/host/pci.c:nvme_irq",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921424,
      "name": "blk_mq_complete_request",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583969328,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969328,
      "name": "blk_mq_complete_request",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request * rq)
```

```json
{
  "name": "blk_mq_complete_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071344,
      "name": "blk_mq_complete_request",
      "external": true,
      "loc": "block/blk-mq.c:657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_job_done",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_rw_aio_do_completion",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:map_request",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071344,
      "name": "blk_mq_complete_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int error</code>
</li>
</ul>
</details>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
