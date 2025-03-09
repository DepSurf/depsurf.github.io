# Function: <code>blk_mq_start_stopped_hw_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582800608,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:929",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/block/virtio_blk.c:virtblk_restore",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock",
        "drivers/md/dm.c:start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582800608,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583078768,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1007",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_restore",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583078768,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583187840,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1076",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_unblock",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583187840,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237520,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1282",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237520,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414976,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1417",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414976,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583623632,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1476",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583623632,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728560,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1600",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728560,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919856,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1598",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919856,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584023152,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584023152,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416832,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1680",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416832,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532576,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1771",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532576,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564464,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1790",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564464,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584975264,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1801",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584975264,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585682112,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2315",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585682112,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586458320,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2458",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586458320,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702064,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2420",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/virtio_blk.c:virtblk_poll",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702064,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974064,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2439",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/virtio_blk.c:virtblk_poll",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974064,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495855040,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495855040,
      "name": "blk_mq_start_stopped_hw_queues",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229203824,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229203824,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290053056,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290053056,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274982436,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274982436,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583991888,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991888,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927744,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927744,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583975648,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975648,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_mq_start_stopped_hw_queues(struct request_queue * q, bool async)
```

```json
{
  "name": "blk_mq_start_stopped_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075200,
      "name": "blk_mq_start_stopped_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075200,
      "name": "blk_mq_start_stopped_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
